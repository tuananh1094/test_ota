set(COMPONENT_SRCS "main.c". 
                   "wifi.c")
set(COMPONENT_ADD_INCLUDEDIRS ".")
# Embed the server root certificate into the final binary
set(COMPONENT_EMBED_TXTFILES /home/tuananh1094/Learn_Test/esp32/esp32-ota/server_certs/ca_cert.pem)

register_component()
