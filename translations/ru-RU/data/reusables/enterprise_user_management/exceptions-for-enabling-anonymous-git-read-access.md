---
ms.openlocfilehash: 625b0ed6920a4f5f1192583b214983b09427734e
ms.sourcegitcommit: fcf3546b7cc208155fb8acdf68b81be28afc3d2d
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 09/10/2022
ms.locfileid: "145067639"
---
{% note %}

**Примечания.**
- Изменить параметры доступа на чтение Git для вилки репозитория нельзя, так как по умолчанию она наследует параметры доступа от корневого репозитория.
- Если общедоступный репозиторий становится частным, анонимный доступ на чтение Git автоматически отключается для этого репозитория и вилок в нем.
- Если репозиторий с анонимной проверкой подлинности содержит ресурсы {% data variables.large_files.product_name_short %}, то ему не удастся загрузить ресурсы {% data variables.large_files.product_name_short %}, так как для них по-прежнему требуется проверка подлинности. Настоятельно рекомендуется не включать анонимный доступ на чтение Git для репозитория с ресурсами {% data variables.large_files.product_name_short %}.

{% endnote %}