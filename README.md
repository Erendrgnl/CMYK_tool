# CMYK_tool
python tool for CMYK images

'''
__main__

import os


imgPath = os.path.join(your_path,"LOGO.png")
img = PIL.Image.open(imgPath)
src = r"D:\Projects\ICM\ICC_profiles\sRGB.icm"
dst = os.path.join(r"D:\Projects\ICM\ICC_profiles","U.S. Web Coated (SWOP) v2.icm")

outImage = colorConversion.convertImage(image=img,conversion_tpye="RGB2CMYK",icc_dst_path=dst,icc_src_path=src)
outimage.show
outimage.image
outimage.c.show

colorConversion.convertPixel(pixel=(128,45,65),conversion_tpye="RGB2CMYK",icc_dst_path=dst,icc_src_path=src)

'''
