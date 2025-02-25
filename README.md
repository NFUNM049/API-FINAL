## i相册

文档名称 | i相册产品需求文档
-|-
产品名称 | i相册
文档状态 | 已完成
文档作者 | 林晓君
发布日期 | 2019.12.23

***
### ppt下载
* ppt下载[地址1](https://github.com/NFUNM049/API-FINAL)
* ppt下载[地址2](https://gitee.com/NFUNM049/api-ppt)

下载整个压缩包即可

***

### 价值主张设计 
#### 背景
随着智能手机的普及，拍照的成本降低，用户拍摄和存储照片的数量也越来越多，大量的照片管理起来效率低下，花费时间成本高。大部分手机相册只是简单的存储图片的功能，没有更加专业管理相册的app，而更加细分的功能如图像分类、脸庞分类、搜索图片功能却有所缺失，有提供相似服务的相册却不够精准，也不够全面化，只能满足用户的基础需求，无法满足用户的精准搜索图片的需要。

#### 加值宣言
i相册app将在拥有基本管理相册功能的基础下，开发了更加有针对性的功能。登录该app的账号设备，免费提供大容量将图片自动保存到云端。
* 主要功能为通过图像识别api对图片进行自动图像分类功能；
* 通过相册聚类api进行图库的脸庞检索，为图库的中人脸进行智能分组、建立专属相册，用户可以更加方便的查看某一目标对象的照片；还可以通过图片中人脸来搜索该人脸所属分组的相片；
* 以及图像搜索功能，用户可以通过输入关键字进行目标对象的检索。用户可以快速查看目标照片，以及获得了更加精准更加全面的图片结果。更加满足用户的需求，提升用户使用相册的体验。
* 图片物体或场景识别，使用了百度通用物体和场景识别，用户可以直接在图片上操作直接获得图片的识别结果，甚至详细的百度百科信息。

#### 面向对象
喜欢记录生活，查看照片回忆的所有年龄段群体。

#### 目的
定格你的记忆 —— i相册。

#### 核心价值 

用户能够在茫茫的照片海中快速找到目标照片，节省时间和效率。

#### 用户痛点

1.用户想要查看她相册所有狗狗的照片。

2.用户想要查看她相册里朋友A的所有照片。

3.用户想要搜索她相册中具有某些特点照片。

4.用户想要知道图片的物体或场景是什么。

#### 用户需求（使用的人工智能要反映到需求列表中）
用户案例 | 使用api | 重要程度
-- | --| --
用户查看照片分类 | 计算机视觉图像分类 | 重要
用户查看相册中某个人的所有照片 | 相册聚类 |重要
用户输入关键或描述搜索目标照片 | 图像搜索 | 重要
用户想知道图片中的物体或场景的信息 | 百度通用物体和场景识别 | 次重要

#### 用户故事
1.小林想要与同学分享手机里保存的可爱狗狗照片，但是照片太多了，一张一张找实在太麻烦了，于是她打开i相册app，在app的图像分类中，他找到了狗狗这个分类文件夹，里面都是她曾经保存的狗狗图片，然后她打开文件夹后与同学分享快乐。

2.毕业几年啦，时间过的真快呀，小林打开相册想要回忆一下青春岁月，想看一下自己以前的照片，但是照片实在太多啦，她实在不想滑到最前去看，于是她打开i相册app，在脸庞分类中找到了自己，点开文件夹后，里面满满都是自己的照片，是根据时间线排序的，她清楚的看到了自己这几年的变化，满满的回忆漫上心头。

3.小林的朋友找他要一张当初他们一起去大草原旅游的合照，但是那是一年前的时候的事情了，翻相册真的好麻烦啊。突然她灵机一动，打开了i相册app，在搜索栏输入“草原合照”，一下子就找到她想要的照片，可太省心啦！

4.小林保存了一张很帅气的男明星的照片，他很想知道他的名字和信息，但是又不想麻烦的打开电脑传图片再然后百度识图，太麻烦啦。然后她发现i相册中，点击右上角的图标，智能识别图片的结果，小林还进行长摁进入一个具体详情页面。小林十分开心，简直太省事了！

#### 人工智能概率性
* face++人脸识别：旷视科技人脸识别技术在人脸比对方面的准确率高达99.5%，误识率低至1%以下；并且旷视的人脸比对算法搭载了活体检测，有99.9%的准确率，所以说这个高准确率是处于行业前列的。

* azure图像分类：2016年，微软凭借152层的残差网络（RESNET），就已经达到了96%的图像识别准确率。

* 百度通用物体和场景识别：准确率绝对值不断提升，目前再次提升7%。支持超过10万类物体和场景识别，接口返回单张图片内的1个或多个物体的名称，并关联百科词条信息，广泛应用于广告及内容推荐等业务场景中。

### 原型

* [i相册原型]( http://nfunm049.gitee.io/ixiangce)，可自行点击查看。
 
* [相册原型下载入口](https://gitee.com/NFUNM049/ixiangce)，有需要自行下载。

1.开屏页面

![开屏.png](https://upload-images.jianshu.io/upload_images/9455364-86d2c38100b65b0a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2.首页/相册

![首页.png](https://upload-images.jianshu.io/upload_images/9455364-edfb7713c7f10542.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

图片详情页-使用百度通用物体和场景识别

![图片详情页-使用图像物体和场景识别.png](https://upload-images.jianshu.io/upload_images/9455364-a16839d7c41da638.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

图片详情页-百度通用物体和场景识别检测结果详情页面
![图片详情页-检测结果详情.png](https://upload-images.jianshu.io/upload_images/9455364-896ebe177bb34a24.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3.快速相册（api）

![快速相册.png](https://upload-images.jianshu.io/upload_images/9455364-632faa0f2e6ccf77.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 图片搜索（使用了图像搜索api）

![搜索功能.png](https://upload-images.jianshu.io/upload_images/9455364-28911fdaa72a0661.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![搜索功能页面2.png](https://upload-images.jianshu.io/upload_images/9455364-f99c234a2937d7a1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 图片分类（使用了图像分类api）

![图片分类页面1.png](https://upload-images.jianshu.io/upload_images/9455364-1bcab7bef174f981.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![图片分类页面2.png](https://upload-images.jianshu.io/upload_images/9455364-ad63ae0ea1bc6e30.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 脸庞分类（使用了相册聚类api）

![脸庞分类页面1.png](https://upload-images.jianshu.io/upload_images/9455364-82ed1b751909eb33.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![脸庞分类页面2.png](https://upload-images.jianshu.io/upload_images/9455364-f52f0181c40be077.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4.我的

![我的.png](https://upload-images.jianshu.io/upload_images/9455364-940494c2e875c5d0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 产品结构图

![i相册产品结构图.2.png](https://upload-images.jianshu.io/upload_images/9455364-8a73373854817629.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 产品功能结构图

![i相册产品功能结构图.2.png](https://upload-images.jianshu.io/upload_images/9455364-400b31d513df4f5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 产品流程图

![产品流程图.png](https://upload-images.jianshu.io/upload_images/9455364-64e99e814e643e04.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### api的调用与选择

#### [相册聚类](https://www.faceplusplus.com.cn/photo-album-clustering/)

*  接口描述：识别相册中照片的人脸，然后照片可根据人脸进行自动聚类，新入库的照片也可按照人脸自动归类。调用者可以通过此API在云端建立或删除人脸相册(Album)，相册可以根据相片中的人脸对相片进行智能分组，调用者也可通过图片中人脸来搜索该人脸所属分组的相片。

* 图片要求:
图片格式：JPG(JPEG)，PNG
图片像素尺寸：最小 48*48 像素，最大 4096*4096 像素
图片文件大小：2MB
最小人脸像素尺寸：系统能够检测到的人脸框为一个正方形，正方形边长的最小值为 150 像素。

*  接口地址：[https://api-cn.faceplusplus.com/imagepp/v1/facealbum/createalbum](https://api-cn.faceplusplus.com/imagepp/v1/facealbum/createalbum)

* 使用比较分析：在使用较低质量或人脸模糊的照片时，精准度将有偏差。有很多平台提供人脸识别的功能，但face++提供相册聚类的功能，能够更加快速的识别相册中的人物并进行自动聚类。**根据多个开放平台（azure、百度ai、阿里云）提供的人脸识别服务对比发现，face++平台的api功能较多、识别相准确性高，总体来说，在人脸识别类的api更有竞争优势同时也更加成熟，性价比最高。**

* 服务示例：
![相册聚类.png](https://upload-images.jianshu.io/upload_images/9455364-d307121edb1498c7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### 图片搜索
* 接口描述：必应图像搜索 API 使你可以搜索和查找类似于Bing.com/images的高质量静态图像和动画图像。 可以将搜索优化为，按属性（包括大小、颜色、许可证和新鲜度）包含或排除图像。 此外，还可以搜索热门图像、上传图像以获取关于图像的见解，并能显示缩略图预览。**可以通过文字进行搜索，功能也更加完善，搜索更加优化。**

* 使用比较分析（阿里云的图片搜索与微软的图片搜索比较）：

[阿里云的图片搜索](https://ai.aliyun.com/imagesearch?spm=a2c4g.11186623.h2v3icoap.191.75462d55RhjP0i)：通过输入具有相同元素或者主体内容的图片，在海量图片库中找到相同或者相似的图片。**前提条件是输入图片进行搜索。**

[微软的图片搜索](https://docs.microsoft.com/zh-cn/azure/cognitive-services/bing-image-search/overview)：**必应图像搜索 API 允许你在应用程序中使用必应的图像搜索功能。 通过向 API 发送搜索查询，可以获取与类似的高质量图像。虽然必应图像搜索 API 提供仅限图像的搜索结果，但是你可以组合或使用其他可用的必应搜索 API在 Web 上查找多种类型的内容。**

* 输入
```
import requests
import matplotlib.pyplot as plt
from PIL import Image
from io import BytesIO

subscription_key = "输入key"
search_url = "https://api.cognitive.microsoft.com/bing/v7.0/images/search"
search_term = "puppies"

headers = {"Ocp-Apim-Subscription-Key" : subscription_key}
params  = {"q": search_term, "license": "public", "imageType": "photo"}
response = requests.get(search_url, headers=headers, params=params)
response.raise_for_status()
search_results = response.json()
thumbnail_urls = [img["thumbnailUrl"] for img in search_results["value"][:16]]
f, axes = plt.subplots(4, 4)
for i in range(4):
    for j in range(4):
        image_data = requests.get(thumbnail_urls[i+4*j])
        image_data.raise_for_status()
        image = Image.open(BytesIO(image_data.content))        
        axes[i][j].imshow(image)
        axes[i][j].axis("off")
plt.show()
```

#### 图像分类
[azure图像分类](https://docs.microsoft.com/zh-cn/azure/cognitive-services/computer-vision/concept-categorizing-images)
* 接口描述：除了标记和说明以外，计算机视觉还返回图像中检测到的基于分类的类别。 不同于标记，类别是在父/子继承层次结构中组织的，并且数量更少（86 个，与数千个标记截然相反）。

* 使用比较分析：目前找到的图像分类api仅有微软的图像分类。微软的人工智能相对来说是比较成熟的。

* 服务示例
![图像分类.png](https://upload-images.jianshu.io/upload_images/9455364-f77d9c8623e45f1b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 输入
```
import requests
# If you are using a Jupyter notebook, uncomment the following line.
# %matplotlib inline
import matplotlib.pyplot as plt
from PIL import Image
from io import BytesIO
import os
import sys

# Add your Computer Vision subscription key and endpoint to your environment variables.
if 'COMPUTER_VISION_SUBSCRIPTION_KEY' in os.environ:
    subscription_key = os.environ['COMPUTER_VISION_SUBSCRIPTION_KEY']
else:
    print("\nSet the COMPUTER_VISION_SUBSCRIPTION_KEY environment variable.\n**Restart your shell or IDE for changes to take effect.**")
    sys.exit()

if 'COMPUTER_VISION_ENDPOINT' in os.environ:
    endpoint = os.environ['COMPUTER_VISION_ENDPOINT']

analyze_url = endpoint + "vision/v2.1/analyze"

# Set image_path to the local path of an image that you want to analyze.
image_path = r"D:\F盘 个人学习练习\大三上\api\timg.jpg"

# Read the image into a byte array
image_data = open(image_path, "rb").read()
headers = {'Ocp-Apim-Subscription-Key': subscription_key,
           'Content-Type': 'application/octet-stream'}
params = {'visualFeatures': 'Categories,Description,Color'}
response = requests.post(
    analyze_url, headers=headers, params=params, data=image_data)
response.raise_for_status()

# The 'analysis' object contains various fields that describe the image. The most
# relevant caption for the image is obtained from the 'description' property.
analysis = response.json()
print(analysis)
image_caption = analysis["description"]["captions"][0]["text"].capitalize()

# Display the image and overlay it with the caption.
image = Image.open(BytesIO(image_data))
plt.imshow(image)
plt.axis("off")
_ = plt.title(image_caption, size="x-large", y=-0.1)
```
#### 百度通用物体和场景识别
* 识别物体和场景：持识别动物、植物、商品、建筑、风景、动漫、食材、公众人物等10万个常见物体及场景，接口返回大类及细分类的名称结果
* 获取百科信息：支持获取图片识别结果对应的百科信息，接口返回百科词条URL、图片和摘要描述，可选择是否需要返回百科信息

* 使用比较分析：

同类产品有azure提供的[计算机视觉服务](https://azure.microsoft.com/zh-cn/services/cognitive-services/)和[腾讯](https://ai.qq.com/product/visionimgidy.shtml#scene)图片识别。**azure和腾讯都单纯的提供对物体和场景的识别，而百度提供服务则更加丰富。百度的通用物体和场景识别除普通的对图像进行识别生成识别结果外，还可以额外提供对应的百度百科、百度词条的信息，这也是百度作为国内知名搜索引擎的优势，并且准确率高，让人信服。**
此外：1.基于百度海量数据，准确率高。2.标签体系丰富，可识别出10万+物体及场景标签，并在不断丰富中，持续提供更精细的识别服务。3.简单易用支持标准化接口封装，调用简单，只需上传单张图片，即可获取识别结果

![百度通用识别.png](https://upload-images.jianshu.io/upload_images/9455364-09b6982e8762a81d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 实现：
在浏览相册时，想知道这张图片中的动物、人物、植物或者其他生物是什么，则可以点击界面右上角的小标符，则可以显示基本的简单识别结果，例如图片中的植物名称、动物名称、名人姓名等等，此外，通过长摁用户获得该图片的智能识别结果以及识别到时百度百科信息、百科词条、图片和描述，还可以点击链接了解更具体的信息

* 输入：
```
import requests
import base64

'''
通用物体和场景识别
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v2/advanced_general"
# 二进制方式打开图片文件
f = open(r"图片", 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '***************************************'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```

#### API使用错误反馈
错误现象处理办法：

1.当用户进行**图像搜索**时，对结果不满意，可以点击下方“存在问题？重新搜索”进行重新搜索结果。

2.当用户发现**物体和场景识别、图像分类、脸庞识别**有误时，可以选择错误的图像进行错误提交。

#### 所使用的api链接
[face++相册聚类](https://www.faceplusplus.com.cn/photo-album-clustering/)

[azure图像分类](https://docs.microsoft.com/zh-cn/azure/cognitive-services/computer-vision/concept-categorizing-images)

[azure必应图像搜索](https://docs.microsoft.com/zh-cn/azure/cognitive-services/bing-image-search/overview)

[百度通用物体和场景识别](https://ai.baidu.com/tech/imagerecognition/general)

