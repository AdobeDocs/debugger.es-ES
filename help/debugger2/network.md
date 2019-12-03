---
description: 'null'
keywords: debugger;experience cloud debugger extension;chrome;extension;network;information
seo-description: 'null'
seo-title: Información de red
title: Información de red
uuid: 839686c9-6e4f-4661-acf6-150ea24dc47f
translation-type: tm+mt
source-git-commit: b9147536b8312599dd3144cac31dea9f0f1c3625

---


# Información de red {#network-information}

To view Network information, click **[!UICONTROL Network]**.

La pantalla Red agrega todas las llamadas de la solución Adobe Experience Cloud realizadas en la página y las muestra en orden de izquierda a derecha. Los parámetros estándar se etiquetan automáticamente con nombres descriptivos y se organizan para agrupar parámetros comunes en la misma función.

![](assets/network.jpg)

Esta pantalla es útil para confirmar que los parámetros utilizados para las integraciones, como el ID de visitante de Experience Cloud o el ID de datos suplementarios, son coherentes en todas las integraciones.

>[!NOTE]
>
>En este momento, no todos los parámetros pasados en las llamadas de solución (por ejemplo, variables de contexto de Analytics, parámetros personalizados de Target o ID de cliente del servicio de Experience Cloud ID) están visibles en la pantalla Red.

Para filtrar la información por solución, seleccione la solución que desee ver en la lista de la navegación izquierda. El siguiente ejemplo se filtra para mostrar solo Analytics:

![](assets/network-analytics.jpg)

Para volver a mostrar todas las soluciones, haga clic en **[!UICONTROL Network]**

Haga clic en un elemento en la vista Red para ver una vista ampliada. Desde la ventana de vista expandida, puede copiar la información mostrada en el portapapeles.

![](assets/network-expand.jpg)

<!--Use the icon at the top of each column to copy the server call URL to your clipboard, where you can paste it into another document for reference or debugging purposes.

![](assets/copy.jpg)-->

Para borrar la lista, haga clic en **[!UICONTROL Remove Events]**.

Para descargar un archivo de Excel que contenga la información de esta pantalla, haga clic en **[!UICONTROL Download]**.