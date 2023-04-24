add_library(mongoose STATIC mongoose.c)

target_link_directories(mongoose
    PUBLIC 
        ${CMAKE_CURRENT_SOURCE_DIR})