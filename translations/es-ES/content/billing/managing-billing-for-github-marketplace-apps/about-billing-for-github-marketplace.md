---
title: Acerca de la facturación para el Mercado GitHub
intro: 'Si instalas una app paga en {% data variables.product.prodname_marketplace %}, tu suscripción comparte la fecha de facturación, el método de pago y el recibo existentes de tu cuenta.'
redirect_from:
  - /github/setting-up-and-managing-billing-and-payments-on-github/about-billing-for-github-marketplace
  - /articles/about-billing-for-github-marketplace
  - /github/setting-up-and-managing-billing-and-payments-on-github/managing-billing-for-github-marketplace-apps/about-billing-for-github-marketplace
versions:
  fpt: '*'
  ghec: '*'
type: overview
topics:
  - Marketplace
shortTitle: Billing for GitHub Marketplace
ms.openlocfilehash: 815303fa5c0c1a006a0bd4bd017039cf1e035f15
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 09/05/2022
ms.locfileid: '145091688'
---
{% data variables.product.prodname_marketplace %} incluye apps con planes de precios gratuitos y pagos. Después de comprar e instalar una app, puedes actualizar, bajar de categoría o cancerla en cualquier momento.

{% data reusables.marketplace.marketplace-apps-only %}

{% data reusables.marketplace.marketplace-org-perms %}

## Métodos de pago y ciclos de facturación para las compras de {% data variables.product.prodname_marketplace %}

Tendrás el mismo método de pago para todas las suscripciones y los planes pagos en todo {% data variables.product.prodname_dotcom %}.

Si tu cuenta personal u organización no tienen un método de pago en el archivo, cuando eliges un plan pago para una app:
- Tu fecha de facturación es hoy.
- Debes agregar un método de pago a tu cuenta personal o a la organización en la que quieres instalar la app.
- Tu método de pago será cargado con el monto total de tu suscripción.
- Tu recibo se envía a la dirección de correo electrónico de facturación o a la principal en el archivo para tu cuenta personal u organización.

Si tu cuenta personal u organización tienen un método de pago existente, cuando eliges un plan pago para una app:
- Al método de pago en el archivo se le cobrará de inmediato un monto prorrateado por el tiempo restante hasta tu próxima fecha de facturación.
- La fecha de facturación mensual o anual para la suscripción de tu app es la misma que la fecha de facturación regular de tu cuenta u organización.
- En tu próxima fecha de facturación, tu recibo detalla los cargos por tu plan {% data variables.product.prodname_dotcom %} pago y tu suscripción a la app.

Cuando eliges un plan pago con una prueba gratuita:
- Debes tener un método de pago existente o agregar un método de pago nuevo para tu cuenta personal o para la organización en la que quieres instalar la app.
- Si no tienes ninguna otra suscripción ni plan pago, se te cobrará el monto total de tu suscripción al finalizar la prueba gratuita de 14 días.
- Si tienes otras suscripciones o planes pagos, una vez que finaliza tu prueba de 14 días, al método de pago en el archivo se le cobrará de inmediato un monto prorrateado por el tiempo restante hasta tu próxima fecha de facturación.
- Si tienes otras suscripciones o planes pagos, en tu próxima fecha de facturación, tu recibo detalla los cargos por tu plan {% data variables.product.prodname_dotcom %} pago y tu suscripción a la app.

{% data reusables.user-settings.context_switcher %}

## Limites de plan unitario

Si eliges un plan unitario (por ejemplo, un plan que cobra por usuario) y excedes las unidades por las que estás pagando, el integrador puede desactivar tu acceso hasta que actualices la app. Para obtener más información, consulte "[Subir de categoría el plan de facturación de una app del {% data variables.product.prodname_marketplace %}](/articles/upgrading-the-billing-plan-for-a-github-marketplace-app)".

## Bajar de categoría una app {% data variables.product.prodname_marketplace %}

Si bajas de categoría la suscripción de tu app a un plan más económico o si cancelas la suscripción de una app paga, tus cambios entrarán en vigencia al finalizar tu ciclo de facturación actual. Tu suscripción se moverá a tu nuevo plan en tu próxima fecha de facturación.

Si cancelas una app en un plan gratuito, tu suscripción terminará de inmediato y perderás el acceso a la app.

{% data reusables.marketplace.downgrade-marketplace-only %}

Si cancelas un prueba gratuita en un plan pago, tu suscripción se cancela de inmediato y perderás el acceso a la app. Para obtener más información, consulte "[Cancelar una app {% data variables.product.prodname_marketplace %}](/articles/canceling-a-github-marketplace-app)"

## Información adicional

- "[Acerca de {% data variables.product.prodname_marketplace %}](/articles/about-github-marketplace)"
- "[Comprar e instalar aplicaciones en el {% data variables.product.prodname_marketplace %}](/articles/purchasing-and-installing-apps-in-github-marketplace)"
- "[Asistencia de {% data variables.product.prodname_marketplace %}](/articles/github-marketplace-support)"
