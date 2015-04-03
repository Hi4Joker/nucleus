# Changelog

### 03.04.2015, Version: 1.1.0

* Base view classes for support libraries has been extracted to separate artifacts.
* There is an ability to NOT put `@RequiresPresenter` annotation now.
* `@RequiresPresenter` annotation has been moved to `view` package.
* `PresenterManager` does not analyse View to find Presenter's class now. It requires presenter's class as an argument.