idf_component_register(SRCS "mqtt_send_data.c"
                    INCLUDE_DIRS "."
                    REQUIRES nvs_flash esp_wifi esp_netif mqtt esp_driver_gpio)
