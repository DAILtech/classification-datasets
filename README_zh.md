# 自然图像分类数据集
公开的中等尺寸自然图像分类数据集(样本数：6万-130万)
| 数据集名称 | 图像尺寸 | 图像数量 | 类别数量 | 开源网址 |
|-----------|---------|----------|----------|----------|
| CIFAR‑10 | 32 × 32 像素| 60,000 张| 10 类 | [huggingface.co](https://huggingface.co/datasets/uoft-cs/cifar10) |
| CIFAR‑100 | 32 × 32 像素| 60,000 张| 100 类 | [huggingface.co](https://huggingface.co/datasets/uoft-cs/cifar100) |
| ImageNet‑1K | 224 × 224 像素| 1,281,167 张| 1,000 类 | [huggingface.co](https://huggingface.co/datasets/timm/imagenet-1k-wds) |
| CINIC‑10 | 32 × 32 像素 | 270,000 张 | 10 类（与 CIFAR‑10 相同类别） | [huggingface.co](https://huggingface.co/datasets/flwrlabs/cinic10) |
| Tiny ImageNet | 64 × 64 像素 | 120,000 张（训练 100,000 张，验证 10,000 张，测试 10,000 张） | 200 类 | [cs231n.stanford.edu](https://cs231n.stanford.edu/reports/2017/pdfs/930.pdf#:~:text=less%20image%20classes,images%20are%20of%20size%2064%C3%9764) |
| ImageNet‑LT（长尾版） | 不定（ImageNet 原始分辨率） | ~135,000 张（训练 115k，测试 20k） | 1,000 类 | [arxiv.org](https://arxiv.org/pdf/2109.05263#:~:text=consists%20of%2062,images%20and%2020k%20test%20images) |
| Places‑LT（长尾版） | 不定（场景照片） | ~99,000 张（训练 62.5k，测试 36.5k） | 365 类 | [arxiv.org](https://arxiv.org/pdf/2109.05263#:~:text=365,class) |
| SUN397 | 不定（各类场景图像） | 108,754 | 397 类 | [pytorch.org](https://pytorch.org/vision/main/generated/torchvision.datasets.SUN397.html#:~:text=The%20SUN397%20or%20Scene%20UNderstanding,397%20categories%20with%20108%E2%80%99754%20images) |
| SVHN（街景门牌号） | 32 × 32 像素 | ≈630,000 张（包含附加训练集） | 10 类（数字 0–9） | [medium.com](tahttps://medium.com/@lostandfound2654/image-classification-on-the-svhn-dataset-34040e2c7d4c#:~:text=The%20Street%20View%20House%20Numbers,used%20to%20help%20with%20training) |
| Food‑101 | 最大边长 512 像素 | 101,000 张 | 101 类 | [pytorch.org](https://pytorch.org/vision/0.18/generated/torchvision.datasets.Food101.html#:~:text=The%20Food,side%20length%20of%20512%20pixels) |
| Food‑251（iFood 2019） | 不定（网络抓取图像） | 160,785 张（训练 120,216，验证 12,170，测试 28,399） | 251 类 | [sites.google.com](https://sites.google.com/view/fgvc6/competitions/ifood-2019#:~:text=our%20last%20year%27s%20dataset%20to,category%20label) |
| Deep（服饰分类） | 不定（提供高分辨率图像） | 289,222 张 | 50 类 | [mmlab.ie.cuhk.edu.hk](https://mmlab.ie.cuhk.edu.hk/projects/DeepFashion/AttributePrediction.html#:~:text=in%20the%20wild) |
| iNaturalist 2017 | 最大边长 800 像素 | 579,184 张训练 + 95,986 张验证 + 182,707 张测试（共约 857,877 张） | 5,089 类 | [openaccess.thecvf.com](https://openaccess.thecvf.com/content_cvpr_2018/papers/Van_Horn_The_INaturalist_Species_CVPR_2018_paper.pdf#:~:text=182%2C707%20test%20images,available%20from%20our%20project%20website2) |
| iNaturalist 2018 | 最大边长 800 像素 | 437,513 张训练 + 24,426 张验证 + 149,394 张测试（共约 611,333 张） | 8,142 类 | [github.com](https://github.com/visipedia/inat_comp/blob/master/2018/README.md) |
| iNat Challenge 2019 | 约 800 × 800 像素 | 268,243 张训练+验证 + 35,350 张测试（共 303,593 张） | 1,010 类 | [arxiv.org](https://arxiv.org/pdf/2102.01863#:~:text=set%2C%20validation%20set%20and%20the,size%20of%20800px%20x%20800px) |
| CLEVR | 320 × 240 像素| 100,000 张（70k 训练，15k 验证，15k 测试） | 不固定 | [cs.stanford.edu](https://cs.stanford.edu/people/jcjohns/clevr/) |
| Country211 | 不定 | 63,300 张| 211 类 | [OpenDataLab](https://opendatalab.com/OpenDataLab/Country211) |
| MiniPlaces（Places88） | 128 × 128 像素| 100,000 张 | 88 类 | [github.com](https://github.com/CSAILVision/miniplaces) |
| MSCOCO | 多样（一般为 640 × 480 或更高） | 330,000 张 | 80 个目标类别，91 个材料类别 | [COCO](https://cocodataset.org/#home) |
| OpenImage V6 Subset | 不定 | 600,000+ | 600+ | [kaggle.com](https://www.kaggle.com/datasets/programmerrdai/open-images-v6) |
| iWildCam 2021 | 多样 | 203,314 张训练图像，60,214 张测试图像 | 206 个物种 | [iWildCam 2021](https://www.kaggle.com/datasets/programmerrdai/open-images-v6) |
| fMoW | 主要为 224 × 224 像素 | 超过 100 万张图像 | 63 | [OpenDataLab](https://www.kaggle.com/datasets/programmerrdai/open-images-v6) |
| GeoDE | 主要为 224 × 224 像素 | 61,940 张图像 | 40 | [GeoDE](https://geodiverse-data-collection.cs.princeton.edu/) |
| Google Landmarks v2（subset） | 不定 | 100,000 张| 1,000+ 类| [github.com](https://geodiverse-data-collection.cs.princeton.edu/) |
