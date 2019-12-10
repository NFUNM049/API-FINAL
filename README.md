## i相册

文档名称 | i相册产品需求文档
-|-
产品名称 | i相册
文档状态 | 进行中
文档作者 | 林晓君
发布日期 | 未定

### 价值主张设计 
#### 背景
用户拍摄和存储照片的数量越来越多，大量的照片管理起来效率低下，时间成本高。大部分手机相册只是简单的存储图片的功能，也没有更加专业管理相册的app，而更加细分的功能如图像分类、脸庞分类、搜索图片功能却有所缺失，有提供相似服务的相册却不够精准，也不够全面化，只能满足用户的基础需求，无法满足用户的精准搜索图片的需要。

#### 加值宣言
i相册app将在拥有基本管理相册功能的基础下，开发了更加有针对性的功能。登录该app的账号设备，免费提供大容量将图片自动保存到云端。主要功能为通过图像识别api进行图像分类功能；通过相册聚类api进行图库的脸庞检索，为每一人建立专属的相册，用户可以更加方便的查看某一目标对象的照片；以及图像搜索功能，用户可以通过输入关键字进行目标对象的检索。用户可以快速查看目标照片，以及获得了更加精准更加全面的图片结果。更加满足用户的需求，提升用户使用相册的体验。

#### 面向对象
喜欢记录生活，查看照片回忆的所有年龄段群体。

#### 目的
定格你的美好记忆 —— i相册。

#### 核心价值 

提供云端管理相册的功能，用户能够在茫茫的照片海中快速找到目标照片，节省时间和效率。

#### 用户痛点
1.用户想要查看她相册所有狗狗的照片。

2.用户想要查看她相册里朋友A的所有照片。

3.用户想要搜索她相册中具有某些特点照片。

#### 用户需求（使用的人工智能要反映到需求列表中）
用户案例 | 使用api | 重要程度
-- | --| --
用户查看照片分类 | 计算机视觉图像分类 | 重要
用户查看相册中某个人的所有照片 | 相册聚类 |重要
用户输入关键或描述搜索目标照片 | 图像搜索 | 重要

#### 用户故事
1.小林想要与同学分享手机里保存的可爱狗狗照片，但是照片太多了，一张一张找实在太麻烦了，于是她打开i相册app，在app的图像分类中，他找到了狗狗这个分类文件夹，里面都是她曾经保存的狗狗图片，然后她打开文件夹后与同学分享快乐。

2.毕业几年啦，时间过的真快呀，小林打开相册想要回忆一下青春岁月，想看一下自己以前的照片，但是照片实在太多啦，她实在不想滑到最前去看，于是她打开i相册app，在脸庞分类中找到了自己，点开文件夹后，里面满满都是自己的照片，是根据时间线排序的，她清楚的看到了自己这几年的变化，满满的回忆漫上心头。

3.小林的朋友找他要一张当初他们一起去大草原旅游的合照，但是那是一年前的时候的事情了，翻相册真的好麻烦啊。突然她灵机一动，打开了i相册app，在搜索栏输入“草原合照”，一下子就找到她想要的照片，可太省心啦！


***

### 原型

* [i相册原型](http://nfunm049.gitee.io/i-image)，可自行点击查看。
 
* [相册原型下载入口](https://gitee.com/NFUNM049/i-image)，有需要自行下载。

1.开屏页面

![开屏.png](https://upload-images.jianshu.io/upload_images/9455364-86d2c38100b65b0a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2.首页/相册

![首页.png](https://upload-images.jianshu.io/upload_images/9455364-edfb7713c7f10542.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

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

![i相册产品结构图.png](https://upload-images.jianshu.io/upload_images/9455364-27d9b88ada5aa705.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 产品功能结构图

![i相册产品功能结构图.png](https://upload-images.jianshu.io/upload_images/9455364-6400fd0d4edfbbc8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### api的调用与选择

#### [相册聚类](https://www.faceplusplus.com.cn/photo-album-clustering/)

*   接口描述：识别相册中照片的人脸，然后照片可根据人脸进行自动聚类，新入库的照片也可按照人脸自动归类。调用者可以通过此API在云端建立或删除人脸相册(Album)，相册可以根据相片中的人脸对相片进行智能分组，调用者也可通过图片中人脸来搜索该人脸所属分组的相片。

* 图片要求:
图片格式：JPG(JPEG)，PNG
图片像素尺寸：最小 48*48 像素，最大 4096*4096 像素
图片文件大小：2MB
最小人脸像素尺寸：系统能够检测到的人脸框为一个正方形，正方形边长的最小值为 150 像素。

*   接口地址：[https://api-cn.faceplusplus.com/imagepp/v1/facealbum/createalbum](https://api-cn.faceplusplus.com/imagepp/v1/facealbum/createalbum)

* **使用比较分析：**在使用较低质量或人脸模糊的照片时，精准度将有偏差。有很多平台提供人脸识别的功能，但face++提供相册聚类的功能，能够更加快速的识别相册中的人物并进行自动聚类。**根据多个开放平台（azure、百度ai、阿里云）提供的人脸识别服务对比发现，face++平台的api功能较多、识别相准确性高，总体来说，在人脸识别类的api更有竞争优势同时也更加成熟，性价比最高。**

* 服务示例：
![相册聚类.png](https://upload-images.jianshu.io/upload_images/9455364-d307121edb1498c7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 输入
```
# -*- coding: utf-8 -*-
import urllib.request
import urllib.error
import time

http_url = 'https://api-cn.faceplusplus.com/facepp/v3/detect'
key = "xxx"
secret = "xxx"
filepath = r"D:\F盘 个人学习练习\大三上\api\timg.jpg"

boundary = '----------%s' % hex(int(time.time() * 1000))
data = []
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'api_key')
data.append(key)
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'api_secret')
data.append(secret)
data.append('--%s' % boundary)
fr = open(filepath, 'rb')
data.append('Content-Disposition: form-data; name="%s"; filename=" "' % 'image_file')
data.append('Content-Type: %s\r\n' % 'application/octet-stream')
data.append(fr.read())
fr.close()
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'return_landmark')
data.append('1')
data.append('--%s' % boundary)
data.append('Content-Disposition: form-data; name="%s"\r\n' % 'return_attributes')
data.append(
    "gender,age,smiling,headpose,facequality,blur,eyestatus,emotion,ethnicity,beauty,mouthstatus,eyegaze,skinstatus")
data.append('--%s--\r\n' % boundary)

for i, d in enumerate(data):
    if isinstance(d, str):
        data[i] = d.encode('utf-8')

http_body = b'\r\n'.join(data)

# build http request
req = urllib.request.Request(url=http_url, data=http_body)

# header
req.add_header('Content-Type', 'multipart/form-data; boundary=%s' % boundary)

try:
    # post data to server
    resp = urllib.request.urlopen(req, timeout=5)
    # get response
    qrcont = resp.read()
    # if you want to load as json, you should decode first,
    # for example: json.loads(qrount.decode('utf-8'))
    print(qrcont.decode('utf-8'))
except urllib.error.HTTPError as e:
    print(e.read().decode('utf-8'))
```

#### 图片搜索
* 接口描述：必应图像搜索 API 使你可以搜索和查找类似于Bing.com/images的高质量静态图像和动画图像。 可以将搜索优化为，按属性（包括大小、颜色、许可证和新鲜度）包含或排除图像。 此外，还可以搜索热门图像、上传图像以获取关于图像的见解，并能显示缩略图预览。**可以通过文字进行搜索，功能也更加完善，搜索更加优化。**

* **使用比较分析（阿里云的图片搜索与微软的图片搜索比较）：**
**[阿里云的图片搜索](https://ai.aliyun.com/imagesearch?spm=a2c4g.11186623.h2v3icoap.191.75462d55RhjP0i)：**通过输入具有相同元素或者主体内容的图片，在海量图片库中找到相同或者相似的图片。**前提条件是输入图片进行搜索。**
**[微软的图片搜索](https://docs.microsoft.com/zh-cn/azure/cognitive-services/bing-image-search/overview)：**必应图像搜索 API 允许你在应用程序中使用必应的图像搜索功能。 通过向 API 发送搜索查询，可以获取与类似的高质量图像。虽然必应图像搜索 API 提供仅限图像的搜索结果，但是你可以组合或使用其他可用的必应搜索 API在 Web 上查找多种类型的内容。

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

* **使用比较分析：**目前找到的图像分类api仅有微软的图像分类。微软的人工智能相对来说是比较成熟的。

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
image_path = "C:/Documents/ImageToAnalyze.jpg"

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
#### API使用错误反馈
错误现象处理办法：
1.当用户进行图像搜索时，对结果不满意，可以点击下方“存在问题？重新搜索”进行重新搜索结果。
2.当用户发现图像分类与脸庞识别有误时，可以选择错误的图像进行错误提交。

#### 所使用的api链接
[face++相册聚类](https://www.faceplusplus.com.cn/photo-album-clustering/)

[azure图像分类](https://docs.microsoft.com/zh-cn/azure/cognitive-services/computer-vision/concept-categorizing-images)

[azure必应图像搜索](https://docs.microsoft.com/zh-cn/azure/cognitive-services/bing-image-search/overview)
