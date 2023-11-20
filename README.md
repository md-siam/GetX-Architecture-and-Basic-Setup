# GetX Architecture

A new Flutter project.

## Getting Started

```tree
    lib
    ├── app
    │   ├── core
    │   │   ├── base
    │   │   │   ├── base_controller.dart
    │   │   │   ├── base_view.dart
    │   │   │   └── page_state.dart
    │   │   ├── binding
    │   │   │   └── initial_binding.dart
    │   │   ├── connection_manager
    │   │   │   ├── connection_manager_binding.dart
    │   │   │   ├── connection_manager_controller.dart
    │   │   │   └── connection_type.dart
    │   │   ├── constants
    │   │   │   ├── app_colors.dart
    │   │   │   ├── app_constants.dart
    │   │   │   ├── app_string_constants.dart
    │   │   │   └── asset_constants.dart
    │   │   ├── middleware
    │   │   │   └── auth_middleware.dart
    │   │   ├── model
    │   │   │   └── app_helper_model
    │   │   │       ├── drop_down_list_item.dart
    │   │   │       ├── drop_down_model.dart
    │   │   │       └── progress_step_percentage_model.dart
    │   │   ├── translations
    │   │   │   ├── bn_bd.dart
    │   │   │   └── en_us.dart
    │   │   ├── utils
    │   │   │   ├── extensions
    │   │   │   │   ├── app_extensions.dart
    │   │   │   │   └── app_validator.dart
    │   │   │   ├── helper
    │   │   │   │   ├── app_helper.dart
    │   │   │   │   ├── auth_helper.dart
    │   │   │   │   ├── date_time_helper.dart
    │   │   │   │   ├── localizationService.dart
    │   │   │   │   ├── print_log.dart
    │   │   │   │   └── shared_value_helper.dart
    │   │   │   └── style
    │   │   │       └── app_style.dart
    │   │   └── widgets
    │   │       ├── cached_network_image
    │   │       │   └── cached_network_image.dart
    │   │       ├── controller
    │   │       │   └── edit_text_controller.dart
    │   │       ├── shimmer
    │   │       │   ├── shimmer_base.dart
    │   │       │   └── shimmer_widgets.dart
    │   │       ├── app_widgets.dart
    │   │       ├── background.dart
    │   │       ├── my_app_bar.dart
    │   │       ├── my_drop_down.dart
    │   │       ├── my_edit_text.dart
    │   │       ├── responsive.dart
    │   │       └── rounded_button.dart
    │   ├── data
    │   │   ├── access_layer
    │   │   │   └── card_list_repo.dart
    │   │   ├── local
    │   │   │   └── card_list_impl.dart
    │   │   └── remote
    │   │       └── card_list_impl.dart
    │   ├── modules
    │   │   ├── cards
    │   │   │   ├── bindings
    │   │   │   │   └── cards_binding.dart
    │   │   │   ├── controllers
    │   │   │   │   └── cards_controller.dart
    │   │   │   └── views
    │   │   │       └── cards_view.dart
    │   │   ├── contacts
    │   │   │   ├── bindings
    │   │   │   │   └── contacts_binding.dart
    │   │   │   ├── controllers
    │   │   │   │   └── contacts_controller.dart
    │   │   │   └── views
    │   │   │       └── contacts_view.dart
    │   │   ├── home
    │   │   │   ├── bindings
    │   │   │   │   └── home_binding.dart
    │   │   │   ├── controllers
    │   │   │   │   └── home_controller.dart
    │   │   │   └── views
    │   │   │       └── home_view.dart
    │   │   ├── main_menu
    │   │   │   ├── binding
    │   │   │   │   └── main_menu_binding.dart
    │   │   │   ├── controller
    │   │   │   │   └── main_menu_controller.dart
    │   │   │   ├── view
    │   │   │   │   └── main_menu_view.dart
    │   │   │   └── main_menu_enum.dart
    │   │   ├── more
    │   │   │   ├── bindings
    │   │   │   │   └── more_binding.dart
    │   │   │   ├── controllers
    │   │   │   │   └── more_controller.dart
    │   │   │   └── views
    │   │   │       └── more_view.dart
    │   │   ├── onboard
    │   │   │   ├── bindings
    │   │   │   │   └── onboard_binding.dart
    │   │   │   ├── controllers
    │   │   │   │   └── onboard_controller.dart
    │   │   │   └── views
    │   │   │       └── onboard_view.dart
    │   │   ├── scan
    │   │   │   ├── bindings
    │   │   │   │   └── scan_binding.dart
    │   │   │   ├── controllers
    │   │   │   │   └── scan_controller.dart
    │   │   │   └── views
    │   │   │       └── scan_view.dart
    │   │   ├── settings
    │   │   │   ├── bindings
    │   │   │   │   └── settings_binding.dart
    │   │   │   ├── controllers
    │   │   │   │   └── settings_controller.dart
    │   │   │   └── views
    │   │   │       └── settings_view.dart
    │   │   └── splash
    │   │       ├── bindings
    │   │       │   └── splash_binding.dart
    │   │       ├── controllers
    │   │       │   └── splash_controller.dart
    │   │       └── views
    │   │           └── splash_view.dart
    │   ├── networkService
    │   │   └── api_endpoint.dart
    │   └── routes
    │       ├── app_pages.dart
    │       └── app_routes.dart
    └── main.dart
```
