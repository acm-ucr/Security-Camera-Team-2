idf_component_register(SRCS "app_main.c"
                       INCLUDE_DIRS "."
                       REQUIRES esp32-camera esp_http_server esp_event esp_wifi nvs_flash)