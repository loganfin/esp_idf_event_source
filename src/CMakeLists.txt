idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES
                        esp_http_server
                        esp_netif
                        log
                        nvs_flash
                        lwip
                        esp_wifi
                        )
