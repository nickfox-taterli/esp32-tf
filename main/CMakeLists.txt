
#
# Main component of TF Micro project 'person_detection_int8'.
#

idf_component_register(
    SRCS detection_responder.cc image_provider.cc main.cc main_functions.cc model_settings.cc app_camera_esp.c
    INCLUDE_DIRS "./include")
