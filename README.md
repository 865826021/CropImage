# CropImage
����facebookͼƬ�ü������������Զ��壬ͼƬ��С���⣬��֤ͼƬ��߱ȣ�֧�����š��϶�

#ʹ�÷���
    var crop = new CropImage({
    realWidth: 500,
    realHeight: 300,
    imageSrc: "https://scontent-sjc.xx.fbcdn.net/hphotos-xpf1/t31.0-8/11082173_1375191982809420_8824827256454539423_o.jpg"
    });
    
    document.appendChild(div, crop.domNode);
    cropImage.startup();
    
    //{
    //w:
    //h:
    //}
    var currentImageSize = crop.getImageSize();
    
    //{
    //l:
    //t:
    //w:
    //h:
    //}
    var cropSize = crop.getCropSize();