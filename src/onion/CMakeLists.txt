add_library(onion onion_codecs.c onion_dict.c onion.c onion_request.c onion_response.c onion_handler.c onion_server.c)

target_link_libraries(onion)