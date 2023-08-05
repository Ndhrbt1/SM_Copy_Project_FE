# copyproject

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

# COPYING PROJECT FROM FE MASTER

## Copy new project

```
1. create new flutter project
2. copy folder lib_newproject fe_master into new project
3. delete folder lib on new project
4. rename folder lib_newproject into lib to replace the oldest lib,
if the test error, just open it and comments all using ctrl+/
5. go to pubspec.yaml on new project then click ctrl+shift+p at the
same time and choose "remove all comments"
6. delete from dependencies until end
7. save your changes
8. go to pubspec.yaml on fe_ master then copy from dependencies until end
9. paste it to pubspec.yaml on new project
10. please note any indents in the folder pubspec.yaml, because if
you put it wrong, for example, excess spaces or no spaces,
it makes your coding error.
11. don't forget to save your changes and wait until the problems
clean
12. if there are many warnings about assets let's go to fe_master
then copy folder assets + fttempplates
13. paste them into new project
14. continue save pubspec.yaml on new project then wait
until the problems clean
15. open folder android > app > build.gradle on fe_master then see
there are a lot of comments //! update this line & //! add this line,
so let's follow the instructions then apply into your new project!
16. please note any indents in the folder build.gradle, because if
you put it wrong, for example, excess spaces or no spaces,
it makes your coding error.
17. don't forget to save your changes.
18. after you finished all steps, you can run your new project
to make sure that your new project can running well (make sure
run the project on folder lib).
```

## Copy New Folder

```
How to create new folder on project based fe_master:

1. select ui_screens  on folder lib
2. right click on ui_screens then click new template folder, make sure
you have installed extensions folder templates by Huuums
3. type your new_folder name for example "a.product_list" a. is
the sign (of alphabet), so that the folders are arranged sequentially
4. open _index.dart on folder "a.product_list" then uncomment the
commented text, then cut that text.
5. go to file _index.dart on folder ui_screens, then copy the text,
only the export 'a.product_list/_index.dart'; which is saved on this
file , for another text let's cut again
6. go to folder xtras and open "a.data.dart" then paste the text,
static Injected<AProductListData> get aProductList => _aProductListData;
final _aProductListData = RM1.inj(AProductListData(), Ctrl.aProductList.init);
for another text let's cut again
7. still on the xtrass open "b.ctrl.dart" then paste the text,
 static AProductListCtrl get aProductList => AProductListCtrl();
8. go to folder app on lib,then select folder navigation,
select "b.routes.dart" , adjust the format to the existing routes,
just change the project name and route name.
9. select "c.route_map.dart" then do the same as in "b.routes.dart"
adjust the format to the existing routes.
10. after that save all the changes, to ensure that the project is still clean,
let's run again
```

## NOTE

```
1. Di sini aku copy pubspecnya dari statemanagement karena belum butuh firebase, tp boleh aja langsung ama firebase bebas.
2. Karena pubspecnya dari state management, jadi  di build gradle nya dependenciesnya tidak di tambah.
3. Ketika ada peringatan dio error , ganti yang error dengan dioexception dan dioexceptiontype.
```
