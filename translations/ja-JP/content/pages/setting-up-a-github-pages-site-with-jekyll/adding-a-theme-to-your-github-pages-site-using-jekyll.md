---
title: Jekyll を使用して GitHub Pages サイトにテーマを追加する
intro: テーマを追加およびカスタマイズすることにより、Jekyll サイトをパーソナライズできます。
redirect_from:
  - /articles/customizing-css-and-html-in-your-jekyll-theme
  - /articles/adding-a-jekyll-theme-to-your-github-pages-site
  - /articles/adding-a-theme-to-your-github-pages-site-using-jekyll
  - /github/working-with-github-pages/adding-a-theme-to-your-github-pages-site-using-jekyll
  - /pages/getting-started-with-github-pages/adding-a-theme-to-your-github-pages-site-with-the-theme-chooser
product: '{% data reusables.gated-features.pages %}'
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Pages
shortTitle: Add theme to Pages site
ms.openlocfilehash: 33969695e96aa0629b2811e2742ca3093e58139a
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/05/2022
ms.locfileid: '147644796'
---
リポジトリへの書き込み権限があるユーザは、Jekyll を使用して {% data variables.product.prodname_pages %} サイトにテーマを追加できます。

{% data reusables.pages.test-locally %}

## テーマを追加する

{% data reusables.pages.navigate-site-repo %} {% data reusables.pages.navigate-publishing-source %}
2. *_config.yml* に移動します。
{% data reusables.repositories.edit-file %}
4. テーマ名のために、ファイルに新しい行を追加します。
   - サポートされているテーマを使用するには、「`theme: THEME-NAME`」と入力します。_THEME-NAME_ の部分は、テーマのリポジトリの README に示されているテーマ名に置き換えてください。 サポートされているテーマの一覧については、{% data variables.product.prodname_pages %} サイトの「[サポートされているテーマ](https://pages.github.com/themes/)」を参照してください。
   ![構成ファイルでサポートされているテーマ](/assets/images/help/pages/add-theme-to-config-file.png)
   - {% data variables.product.prodname_dotcom %} でホストされているその他の任意の Jekyll テーマを使うには、「`remote_theme: THEME-NAME`」と入力します。THEME-NAME の部分は、テーマのリポジトリの README に表示されている名前に置き換えます。
   ![構成ファイルでサポートされていないテーマ](/assets/images/help/pages/add-remote-theme-to-config-file.png) {% data reusables.files.write_commit_message %} {% data reusables.files.choose-commit-email %} {% data reusables.files.choose_commit_branch %} {% data reusables.files.propose_file_change %}

## テーマの CSS をカスタマイズする

{% data reusables.pages.best-with-supported-themes %}

{% data reusables.pages.theme-customization-help %}

{% data reusables.pages.navigate-site-repo %} {% data reusables.pages.navigate-publishing-source %}
1. _/assets/css/style.scss_ という新しいファイルを作成します。
2. ファイルの先頭に、以下の内容を追加します。
  ```scss
  ---
  ---

  @import "{% raw %}{{ site.theme }}{% endraw %}";
  ```
3. カスタム CSS または Sass (インポート ファイルも含む) があれば、`@import` 行の直後に追加します。

## テーマの HTML レイアウトをカスタマイズする

{% data reusables.pages.best-with-supported-themes %}

{% data reusables.pages.theme-customization-help %}

1. {% data variables.product.prodname_dotcom %} 上で、テーマのソースリポジトリにアクセスします。 たとえば、Minima のソース リポジトリは https://github.com/jekyll/minima です。
2. *_layouts* フォルダー内で、テーマの _default.html_ ファイルに移動します。
3. ファイルの内容をコピーします。
{% data reusables.pages.navigate-site-repo %} {% data reusables.pages.navigate-publishing-source %}
6. *_layouts/default.html* という名前のファイルを作成します。
7. 先ほどコピーしたデフォルトのレイアウトコンテンツを貼り付けます。
8. 必要に応じてレイアウトをカスタマイズします。

## 参考資料

- [新しいファイルの作成](/articles/creating-new-files)
