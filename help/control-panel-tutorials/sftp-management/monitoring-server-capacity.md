---
title: Övervaka serverkapacitet
description: Med kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans och lägga till IP-adresser i tillåtelselistor.
feature: SFTP Management
topics: Control Panel
audience: administrator
kt: 3266
thumbnail: 27270.jpg
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: 7b2c1ac95dc59ab0c9d8098d76a04af94f273dc8
workflow-type: tm+mt
source-wordcount: '211'
ht-degree: 82%

---


# Övervaka serverkapacitet

På Kontrollpanelen kan du övervaka och hantera SFTP-lagringen per instans.

## Åtkomst till [!UICONTROL Control Panel] för att hantera underdomäner

För att få åtkomst till hantering av underdomäner via [!UICONTROL Control Panel] ska du gå till:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > [!UICONTROL Solution picker]: [!UICONTROL Campaign] > **[!UICONTROL Control Panel]**-kort > **[!UICONTROL Subdomains & Certificates]**-kort

   eller
* Direkt från webbadressen: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Övervaka serverkapacitet, [!UICONTROL allow list] IP-adresser och lägga till SSH-nycklar

I den här videon förklaras hur du kommer åt [!UICONTROL Adobe Campaign Control Panel] och var du kan övervaka lagringen av SFTP-servrar.

>[!VIDEO](https://video.tv.adobe.com/v/27270?quality=12)

### Beskrivning av gränssnittet

**Instanser:** endast de instanser som du har administratörsbehörighet till visas.

**Jobbloggar:** endast jobb som körts i [!UICONTROL Control Panel] visas. De jobb som utfördes utanför [!UICONTROL Control Panel] inkluderas inte (såsom arbetsflöden som körs osv.)

Loggarna innehåller endast de jobb som har körts av administratören för din organisation. Om det finns flera organisationer visas inte loggarna för andra organisationer i jobbloggarna

**Fliken Lagring:** rubriken visar de tre mest använda servrarna. Om du har fler än tre servrar kan du se resterande på fliken [!UICONTROL Storage].

**Varningsmeddelande:**

* Orange – servern används till 80 %
* Röd – servern används till 90 %

## Ytterligare resurser

* [Generera en SSH-nyckel](./generate-ssh-key.md)