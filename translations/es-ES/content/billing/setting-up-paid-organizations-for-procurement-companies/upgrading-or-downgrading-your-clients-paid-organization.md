---
title: Subir o bajar de categoría la organización paga de tu cliente
intro: Los gerentes de facturación pueden subir o bajar de categoría la organización paga de un cliente en cualquier momento.
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/upgrading-or-downgrading-your-clients-paid-organization
  - /articles/upgrading-or-downgrading-your-client-s-paid-organization
  - /articles/upgrading-or-downgrading-your-clients-paid-organization
  - /github/setting-up-and-managing-billing-and-payments-on-github/setting-up-paid-organizations-for-procurement-companies/upgrading-or-downgrading-your-clients-paid-organization
versions:
  fpt: '*'
  ghec: '*'
type: how_to
topics:
  - Organizations
  - Upgrades
shortTitle: Upgrade or downgrade
ms.openlocfilehash: 2309c89fabf2a81aab18df90b8c545f0f3f684e1
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: '145091590'
---
{% data reusables.organizations.reseller-ask-to-become-billing-manager %}

{% tip %}

**Sugerencias**:
- Antes de actualizar la organización del cliente, puede [ver o actualizar el método de pago en el archivo de la organización](/articles/adding-or-editing-a-payment-method).
- Estas indicaciones son para subir o bajar de categoría organizaciones en la *suscripción por puesto*. Si el cliente paga {% data variables.product.product_name %} mediante un plan *heredado por repositorio*, puede actualizar o [cambiar](/articles/downgrading-your-github-subscription) su plan heredado o [cambiar la organización a un plan de precio por puesto](/articles/upgrading-your-github-subscription).

{% endtip %}

## Subir de categoría la cantidad de asientos pagos de una organización

{% data reusables.organizations.billing-settings %} {% data reusables.dotcom_billing.add-seats %} {% data reusables.dotcom_billing.number-of-seats %} {% data reusables.dotcom_billing.confirm-add-seats %}

Después de agregar asientos, al método de pago archivado para la organización se le cobrará un monto prorrateado en función de la cantidad de asientos que agregues y la cantidad de tiempo que quede en tu ciclo de facturación.

## Bajar la categoría de la cantidad de asientos pagos de una organización a gratuita

{% data reusables.organizations.billing-settings %} {% data reusables.dotcom_billing.downgrade-org-to-free %} {% data reusables.dotcom_billing.confirm_cancel_org_plan %}
