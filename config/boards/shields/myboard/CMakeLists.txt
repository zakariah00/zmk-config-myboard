if(SHIELD_MYBOARD)
    zmk_subdir_obj_init()
    zmk_subdir_source_obj(source/pro_micro_transform.c) # Note: Only if using a transform, otherwise standard boilerplate below is safer
endif()
