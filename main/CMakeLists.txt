idf_component_register(SRCS "temp-logger-client-main.c"
                    PRIV_REQUIRES spi_flash
                    INCLUDE_DIRS ""
                    REQUIRES esp_wifi
                    REQUIRES nvs_flash
                    )
