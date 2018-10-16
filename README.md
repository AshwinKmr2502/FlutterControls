![pub](https://img.shields.io/pub/v/easy_listview.svg)

# easy_listview

A simple widget to help you to build ListView with header, footer, divider, and load more function.

## Usage

Simple constructor for widget.

```dart
var listWidget = new EasyListView(
          headerSliverBuilder: headerSliverBuilder,   // SliverAppBar...etc.
          headerBuilder: headerBuilder,               // Header Widget Builder
          footerBuilder: footerBuilder,               // Footer Widget Builder 
          itemCount: itemCount,
          itemBuilder: itemBuilder,
          dividerBuilder: dividerBuilder,             // Custom Divider Builder
          loadMore: hasNextPage,                      // Load more flag
          onLoadMore: onLoadMoreEvent,                // Load more callback
          foregroundWidget: foregroundWidget,         // Widget witch overlap on ListView
          
        );
```

## Example

There is an example in the repo.

# Use this package as a library
## 1. Depend on it
Add this to your package's pubspec.yaml file:


```
dependencies:
  easy_listview: "^0.0.7"
```

## 2. Install it
You can install packages from the command line:
with Flutter:

```
$ flutter packages get
```
Alternatively, your editor might support flutter packages get. Check the docs for your editor to learn more.

## 3. Import it
Now in your Dart code, you can use:

```
import 'package:easy_listview/easy_listview.dart';
```
