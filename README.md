# Master plan - Flutter training

## I. Dart Language
### Mục tiêu:
- Làm quen với cú pháp của ngôn ngữ Dart và vận dụng vào những bài toán cụ thể.
- Hiểu được những điểm đặc trưng và khác biệt của Dart và những ngôn ngữ lập trình hướng đối tượng khác.
- Nắm được và áp dụng Asynchronous Programming trong Dart.
#### 1. Basic Dart Language
- [Language tour](https://dart.dev/language) | [Tìm hiểu về ngôn ngữ lập trình Dart](https://fxstudio.dev/tim-hieu-ve-ngon-ngu-lap-trinh-dart/)
- [Learning Dart as a Swift developer](https://dart.dev/guides/language/coming-from/swift-to-dart)
- [Dart Pad](https://dartpad.dev) -  a tool for creating effective and engaging educational content for Dart and Flutter users.
#### 2. Asynchronous Programming
- [Async-Await](https://dart.dev/codelabs/async-await) | [Lập trình bất đồng bộ với future, async, await](https://viblo.asia/p/flutter-lap-trinh-bat-dong-bo-voi-future-async-await-oOVlYpLaZ8W)
- [Streams](https://dart.dev/tutorials/language/streams)
- [Streams and Futures](https://www.kodeco.com/32851541-dart-futures-and-streams#:~:text=A%20Future%20represents%20a%20one,a%20line%20at%20a%20time)
- [Sự khác biệt giữa Futures và Streams](https://magz.techover.io/2022/04/06/khac-biet-giua-future-va-stream/)

## II. Flutter Tutorial
### Mục tiêu:
* Nắm được cơ bản về Flutter, các ưu nhược điểm, lý do tại sao chọn Flutter so với native hay các nền tảng cross-platform khác.
* Setup môi trường Flutter và chạy được app đầu tiên.
* Nắm được cơ bản và biết cách xây dựng các UI Widget trong Flutter
	* View
	  * Text, Image, Button, Icon,...
	* ViewGroup
		* Container, Row, Column, Stack, Expanded, ConstrainedBox, ScrollView,...
	* Dynamic User Interface
	  * ListView, GridView, ExpansionTile,...
* Hiểu được sự khác nhau giữa Stateless và Stateful Widget.
* Biết cách navigate giữa các screen.
* Biết cách làm việc với dữ liệu qua internet.
* Biết cách lưu trữ dữ liệu vào local database.
#### 1. Flutter Introduction
- [Giới thiệu về Flutter](https://fxstudio.dev/gioi-thieu-ve-flutter/)
- [Mobile app cross-platform, how it works](https://medium.com/@duytq94/mobile-app-cross-platform-how-it-works-4aee105d4f26)
- [Flutter vs Native](https://surf.dev/flutter-vs-native/)
#### 2. Flutter Setup
- [macOS](https://docs.flutter.dev/get-started/install/macos) | [Windows](https://docs.flutter.dev/get-started/install/windows)
- [Setup an Editor](https://docs.flutter.dev/get-started/editor?tab=vscode)
- [Cài đặt Flutter SDK & Hello world](https://fxstudio.dev/cai-dat-flutter-sdk-hello-world/)
- [Flutter Hot Reload](https://docs.flutter.dev/development/tools/hot-reload)
- [Flutter CLI](https://docs.flutter.dev/reference/flutter-cli)
#### 3. Flutter Tutorial
* [Học Flutter từ cơ bản đến nâng cao](https://viblo.asia/p/hoc-flutter-tu-co-ban-den-nang-cao-phan-1-lam-quen-co-nang-flutter-4dbZNJOvZYM) - Series 7 phần.
* Introduction to [Declarative UI](https://docs.flutter.dev/get-started/flutter-for/declarative)
* Introduction to [Widgets](https://docs.flutter.dev/development/ui/widgets-intro)
* [Navigation and routing](https://docs.flutter.dev/ui/navigation)
* Networking
	* [Networking in flutter](https://docs.flutter.dev/development/data-and-backend/networking)
	* [http](https://pub.dev/packages/http) for networking
	* [Dio](https://pub.dev/packages/dio)-  powerful HTTP client of dart
  * [Retrofit](https://medium.com/mindful-engineering/retrofit-the-easiest-way-to-call-rest-apis-is-flutter-fe55d1e7c5c2)
* [JSON and serialization](https://docs.flutter.dev/data-and-backend/json)
* [Persistant](https://docs.flutter.dev/cookbook/persistence)
  * [Store key-vaue pair](https://docs.flutter.dev/cookbook/persistence/key-value)
  * [Sqlite database](https://docs.flutter.dev/cookbook/persistence/sqlite)
  * [hive](https://pub.dev/packages/hive)
* [Ứng dụng flutter đầu tiên](https://fxstudio.dev/ung-dung-flutter-dau-tien/)
#### 4. Demo App
Tạo 1 ứng dụng shopping
    
  Screen one - Home screen 
   -  On main screen show list of products - [API](https://fakestoreapi.com/products)
      
   -  Open product detail on it’s click - [API](https://fakestoreapi.com/products/1)
      
   -  Add option to search products by categories - [API](https://fakestoreapi.com/products/categories)
      
   -  Add option to check out all product in cart
 
  Screen two - Detail screen
   -  Show full detail with images and description 
   -  Add option to add/remove the product from the cart ( Add/delete an item in local database)  

## III. Flutter State Management
### Mục tiêu:
- Hiểu được state management là gì và biết được các state management hay được sử dụng trong Flutter.
- Tìm hiểu về GetX và viết 1 app demo sử dụng GetX.
#### 1. State Management
- [Introduction](https://docs.flutter.dev/development/data-and-backend/state-mgmt/intro) to state management
- [GetX State Management](https://github.com/jonataslaw/getx)
- [GetX Tutorial](https://blog.logrocket.com/ultimate-guide-getx-state-management-flutter/)
#### 2. Demo App

## IV. Flutter Environment Management
- [Flutter Flavor](https://github.com/vanle57/flutter-flavor)

## V. Flutter Advance
- [Developing packages and plugin](https://docs.flutter.dev/packages-and-plugins/developing-packages)
- [Using native code in Flutter](https://docs.flutter.dev/platform-integration/platform-channels)
- [Add Flutter to existing native app](https://docs.flutter.dev/add-to-app)
