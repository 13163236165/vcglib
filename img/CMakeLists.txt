
SET(img_Head
img.h
img_attributes.h
img_base.h
img_convert.h
img_cs_base.h
img_filter.h
img_image.h
img_info.h
img_io.h
img_scalar.h
)

set(img_SRC
img_image.cpp
)

#Source_Group("img" FILES ${img_Files})

Add_Library(imglib STATIC ${img_Head} ${img_SRC})