
#
# Main component of TF Micro project 'person_detection'.
#

idf_component_register(
    SRCS esp/main.cc main_functions.cc detection_responder.cc image_provider.cc model_settings.cc person_detect_model_data.cpp 
    INCLUDE_DIRS "")
