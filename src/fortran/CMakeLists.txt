add_executable(diffusion_fortran diffusion.F90)

target_link_libraries(diffusion_fortran PRIVATE opencmisslibs mpi)

install(TARGETS diffusion_fortran DESTINATION bin)
