---
title: EF Core e EF6 – Qual é o certo para você
author: rowanmiller
ms.author: divega
ms.date: 10/27/2016
ms.assetid: 288f825b-b3e6-4096-971b-d0a1cb96770e
uid: efcore-and-ef6/choosing
ms.openlocfilehash: f0a632902384a65ea3cddf752ad262c7a2e89e2e
ms.sourcegitcommit: 2ef0a4a90b01edd22b9206f8729b8de459ef8cab
ms.translationtype: HT
ms.contentlocale: pt-BR
ms.lasthandoff: 03/20/2018
---
# <a name="ef-core-and-ef6-which-one-is-right-for-you"></a>EF Core e EF6: Qual é o certo para você

As informações a seguir ajudarão você a escolher entre o Entity Framework Core e o Entity Framework 6.

## <a name="guidance-for-new-applications"></a>Orientação para novos aplicativos

Considere usar o EF Core para novos aplicativos se quiser aproveitar todos os seus recursos e caso seu aplicativo não exija recursos ainda não implementados no EF Core.

Para utilizar o EF6, é necessário ter o .NET Framework 4.0 ou uma versão posterior. O EF6 só é compatível com o Windows, ou seja, não pode ser executado no .NET Core e não é compatível com outros sistemas operacionais. No entanto, ainda é uma opção viável para novos aplicativos, desde que essas restrições sejam aceitáveis e o aplicativo não exija novos recursos do EF Core que não estão disponíveis no EF6.

Examine [Comparação de Recursos](features.md) para ver se o EF Core pode ser uma escolha adequada para o seu aplicativo.

## <a name="guidance-for-existing-ef6-applications"></a>Orientação para aplicativos EF6 existentes

Devido às mudanças fundamentais no EF Core, não recomendamos tentar mover um aplicativo EF6 para o EF Core, a menos que você tenha um motivo convincente para fazer essa alteração. Se você quiser mudar para o EF Core a fim de usar os novos recursos, esteja ciente das limitações antes de começar. Examine [Comparação de Recursos](features.md) para ver se o EF Core pode ser uma escolha adequada para o seu aplicativo.

**Veja a mudança do EF6 para o EF Core como uma portabilidade em vez de uma atualização.** Para saber mais, confira [Portabilidade do EF6 para o EF Core](porting/index.md).
