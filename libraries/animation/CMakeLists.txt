set(TARGET_NAME animation)

# use setup_hifi_library macro to setup our project and link appropriate Qt modules
setup_hifi_library(Network Script)

link_hifi_libraries(shared gpu model fbx)

# call macro to include our dependency includes and bubble them up via a property on our target
include_dependency_includes()