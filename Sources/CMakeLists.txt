target_sources(xbooz_xform
               PRIVATE
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/allocate_boozer.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/booz_jac.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/booz_params.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/booz_persistent.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/boozer_coords.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/boozer_gij.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/boozer_metric.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/boozer_xform.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/boozer.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/foranl.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/free_mem_boozer.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/harfun.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/read_wout_booz.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/root.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/setup_booz.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/transpmn.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/trigfunc.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/vcoords.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/vcoords_gijb.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/write_boozmn.f>
               $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/write_polcut.f>
)
