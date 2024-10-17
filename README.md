# Background-extraction
import cv2
# path= images path
images = [cv2.imread(file) for file in glob.glob(path)]
for image in(images):    
    Res=[]  
    T=[]  

    #############  image importation
    # fig=plt.figure()
    # plt.title("image d'origine")
    # plt.imshow(image)
    # plt.show()  
    
    #############  back ground extraction
    image1= remove(image)
    
    # fig=plt.figure()
    # plt.title("image d'origine without background")
    # plt.imshow(image1)
    # plt.show()  
