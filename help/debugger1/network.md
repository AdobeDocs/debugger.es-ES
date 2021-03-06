---
description: Pantalla de información de red de Experience Cloud Debugger
keywords: debugger;extensión de experience cloud debugger;chrome;extensión;red;información
seo-description: Experience Cloud Debugger Network Information screen
seo-title: Network Information
title: Experience Cloud Debugger de información de red
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
exl-id: 9a758088-e87f-42a6-8410-24eb84d0d37a
source-git-commit: 2778ba78de3350ed1da01d452e303476b04c0303
workflow-type: tm+mt
source-wordcount: '221'
ht-degree: 97%

---

# Información de red{#network-information}

Para ver la información de red, haga clic en **[!UICONTROL Network]**.

La pantalla Red agrega todas las llamadas de la solución Adobe Experience Cloud realizadas en la página y las muestra en orden de izquierda a derecha. Los parámetros estándar se etiquetan automáticamente con nombres descriptivos y se organizan para agrupar parámetros comunes en la misma función.

>[!TIP]
>
>Esta pantalla es útil para confirmar que los parámetros utilizados para las integraciones, como el ID de visitante de Experience Cloud o el ID de datos suplementarios, son coherentes en todas las integraciones.

>[!NOTE]
>
>En este momento, no todos los parámetros pasados en las llamadas de solución (por ejemplo, variables de contexto de Analytics, parámetros personalizados de Target o ID de cliente del servicio de Experience Cloud ID) están visibles en la pantalla Red.

Para ver toda la información, seleccione **[!UICONTROL All]**.

También puede filtrar la información por solución. Seleccione las soluciones que desea ver. Puede ver varias soluciones al mismo tiempo. Se resaltan los filtros de solución seleccionados.

![](assets/network.jpg)

Haga clic en un elemento en la vista Red para verlo más grande. Desde la ventana de vista expandida, puede copiar la información mostrada en el portapapeles.

![](assets/network-jsversion.jpg)

Utilice el icono de la parte superior de cada columna para copiar la URL de la llamada al servidor en el portapapeles, donde puede pegarla en otro documento con fines de referencia o depuración.

![](assets/copy.jpg)
