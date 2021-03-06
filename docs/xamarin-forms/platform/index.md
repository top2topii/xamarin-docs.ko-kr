---
title: Xamarin.Forms 플랫폼 기능
description: 이 가이드는 플랫폼별 기능들을 Xamarin.Forms 앱에서 다양한 기술을 사용하여 활용할 수 있는 방법을 설명합니다.
ms.prod: xamarin
ms.assetid: 2C6CE42C-E380-4BB9-90CC-D0F4E60C4C03
ms.technology: xamarin-forms
author: davidbritch
ms.author: dabritch
ms.date: 01/08/2018
ms.openlocfilehash: 3f0156926f8d7a31e2e80318d7b05a909f158653
ms.sourcegitcommit: 395774577f7524b57035c5cca3c9034a4b636489
ms.translationtype: MT
ms.contentlocale: ko-KR
ms.lasthandoff: 01/10/2019
ms.locfileid: "54207728"
---
# <a name="xamarinforms-platform-features"></a>Xamarin.Forms 플랫폼 기능

Xamarin.Forms는 확장이 용이하고,  [Effects](~/xamarin-forms/app-fundamentals/effects/index.md), [Custom Renderers](~/xamarin-forms/app-fundamentals/custom-renderer/index.md), [DependencyService](~/xamarin-forms/app-fundamentals/dependency-service/index.md), [MessagingCenter](~/xamarin-forms/app-fundamentals/messaging-center.md) 등을 사용하여 플랫폼별 기능들을 통합할 수 있습니다.

## <a name="androidandroidindexmd"></a>[Android](android/index.md)

이 가이드에서는 Xamarin.Forms 및 기존 Xamarin.Forms Android 앱을 업데이트 하 여 재질 디자인을 구현 하는 방법을 제공한 Android 플랫폼별-설명 합니다.

## <a name="device-classdevicemd"></a>[장치 클래스](device.md)

`Device` 클래스로 플랫폼에 따른 행동을 공유된 코드에서 구현하는 방법과 XAML을 사용한 유저 인터페이스를 만드는 방법을 소개합니다. 또한, 백그라운드 스레드에서 UI 컨트롤을 수정할 때 중요한 `BeginInvokeOnMainThread`에 대해서도 다룹니다.

## <a name="iosiosindexmd"></a>[iOS](ios/index.md)

이 가이드에서는 Xamarin.Forms 및 추가 iOS를 통한 스타일 지정을 수행 하는 방법을 제공한 iOS 플랫폼 구체적인 설명 **Info.plist** 고 `UIAppearance` API.

## <a name="native-formsnative-formsmd"></a>[네이티브 양식](native-forms.md)

Native Forms는 Xamarin.Forms의 파생된 [ `ContentPage` ](xref:Xamarin.Forms.ContentPage) 페이지들을 네이티브 Xamarin.iOS, Xamarin.Android 및 유니버설 Windows 플랫폼(UWP) 프로젝트에서 사용할 수 있게 파생합니다.

## <a name="native-viewsnative-viewsindexmd"></a>[네이티브 뷰](native-views/index.md)

Xamarin.Forms에서 iOS, Android 및 유니버설 Windows 플랫폼의 네이티브 뷰를 직접 참조할 수 있습니다. 속성과 이벤트 핸들러는 네이티브 뷰에서 설정할 수 있으며, Xamarin.Forms 뷰와 상호작용할 수 있습니다.

## <a name="platform-specificsplatform-specificsindexmd"></a>[플랫폼별](platform-specifics/index.md)

Platform-Specifics는 특정 플랫폼에서만 가능한 기능들을 Custom renderer 또는 Effects 등을 사용하지 않고도 구현할 수 있게 합니다. 또한 vendor 효과 사용 하 여 자신의 플랫폼별을 만들 수 있습니다.

## <a name="windowswindowsindexmd"></a>[Windows](windows/index.md)

이 가이드는 Windows 플랫폼별 Xamarin.Forms 및 UWP 프로젝트를 기존 Xamarin.Forms 솔루션에 추가 하는 방법에서 제공을 설명 합니다.
