- [嵌入式软件工程师笔试面试指南（EmbeddedSoftwareEngineerInterview）](#嵌入式软件工程师笔试面试指南embeddedsoftwareengineerinterview)
  - [嵌入式软件笔试面试知识点总结](#嵌入式软件笔试面试知识点总结)
  - [名企笔试真题](#名企笔试真题)
  - [面试技巧](#面试技巧)
  - [面经总结](#面经总结)
  - [PDF获取方式](#pdf获取方式)
  - [勘误](#勘误)
  - [赞赏](#赞赏)
  

**申明：本资料部分内容转载自网络，请勿用于商业用途。如有侵权，请联系作者删除。**

作者在准备秋招的过程中，整理了一些资料，最后顺利拿到了**oppo，小米，海康威视，兆易创新，全志科技**等十余家公司的offer。现将这部分资料分享出来，希望能对大家有帮助！

如果大家在网上看到了不错的资料，或者在笔试面试中遇到了资料中没有的知识点，大家可以关注我的公众号联系我，及时反馈给我。资料如有错误或者不合适的地方，请及时联系作者。



<font color=#0000FF size=4>整理不易，**希望大家能给个star支持下**，让我有继续更新下去的动力。</font>

最后，祝各位老板，offer多多，钱多多，跳槽薪资double!



# 嵌入式软件工程师笔试面试指南（EmbeddedSoftwareEngineerInterview）

[![alt text](https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-%E5%B5%8C%E5%85%A5%E5%BC%8F%E4%B8%8ELinux%E9%82%A3%E4%BA%9B%E4%BA%8B-blue)](#pdf获取方式)[![alt text](https://img.shields.io/badge/CSDN-%E5%B5%8C%E5%85%A5%E5%BC%8F%E4%B8%8ELinux%E9%82%A3%E4%BA%9B%E4%BA%8B-lightgrey)](https://blog.csdn.net/qq_16933601?spm=1000.2115.3001.5343)[![alt text](https://img.shields.io/badge/%E5%8D%9A%E5%AE%A2%E5%9B%AD-%E5%B5%8C%E5%85%A5%E5%BC%8F%E4%B8%8ELinux%E9%82%A3%E4%BA%9B%E4%BA%8B-red)](https://www.cnblogs.com/dongxb/)[![alt text](https://img.shields.io/badge/%E7%9F%A5%E4%B9%8E-%E4%BB%B2%E4%B8%80-orange)](https://www.zhihu.com/people/simple-95-72)[![alt text](https://img.shields.io/badge/%E7%89%9B%E5%AE%A2-%E5%B5%8C%E5%85%A5%E5%BC%8F%E4%B8%8ELinux%E9%82%A3%E4%BA%9B%E4%BA%8B-green)](https://www.nowcoder.com/profile/913155792)[![alt text](https://img.shields.io/badge/%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%9F%BA%E7%A1%80-%E7%A1%AC%E6%A0%B8%E5%A5%BD%E6%96%87-yellow)](https://mp.weixin.qq.com/mp/appmsgalbum?action=getalbum&__biz=Mzg5ODUxNDMxMA==&scene=23&album_id=1697392020677312514&count=3#wechat_redirect)[![alt text](https://img.shields.io/badge/PDF%E6%96%87%E6%A1%A3-%E5%85%8D%E8%B4%B9%E8%8E%B7%E5%8F%96-brightgreen)](#pdf获取方式)

   







## 嵌入式软件笔试面试知识点总结

[C/C++](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93/CandC%2B%2B.md)

[数据结构与算法分析](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93/%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8E%E7%AE%97%E6%B3%95%E5%88%86%E6%9E%90.md)

[ARM体系与架构](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93/ARM%E4%BD%93%E7%B3%BB%E4%B8%8E%E6%9E%B6%E6%9E%84.md)

[Linux驱动](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93/Linux%E9%A9%B1%E5%8A%A8.md)

[操作系统](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93/%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F.md)

[网络编程](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93/%E7%BD%91%E7%BB%9C%E7%BC%96%E7%A8%8B.md)

## 名企笔试真题

[小米](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E5%90%8D%E4%BC%81%E7%AC%94%E8%AF%95%E7%9C%9F%E9%A2%98/%E5%B0%8F%E7%B1%B3%E5%B5%8C%E5%85%A5%E5%BC%8F%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%AC%94%E8%AF%95%E9%A2%98%E7%9B%AE%E8%A7%A3%E6%9E%90.md)

[联发科](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E5%90%8D%E4%BC%81%E7%AC%94%E8%AF%95%E7%9C%9F%E9%A2%98/%E5%8C%97%E4%BA%AC%E8%81%94%E5%8F%91%E7%A7%91%E5%B5%8C%E5%85%A5%E5%BC%8F%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%AC%94%E8%AF%95%E9%A2%98%E7%9B%AE%E8%A7%A3%E6%9E%90.md)

[兆易创新](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E5%90%8D%E4%BC%81%E7%AC%94%E8%AF%95%E7%9C%9F%E9%A2%98/%E5%85%86%E6%98%93%E5%88%9B%E6%96%B0%E5%B5%8C%E5%85%A5%E5%BC%8F%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%AC%94%E8%AF%95%E9%A2%98%E7%9B%AE%E8%A7%A3%E6%9E%90.md)

## 面试技巧

[如何获取就业信息](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%AC%94%E8%AF%95%E9%9D%A2%E8%AF%95%E6%8A%80%E5%B7%A7/%E6%A0%A1%E6%8B%9B%E4%BF%A1%E6%81%AF%E8%8E%B7%E5%8F%96%E6%B8%A0%E9%81%93.md)

[如何在面试中介绍自己的项目经验](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%AC%94%E8%AF%95%E9%9D%A2%E8%AF%95%E6%8A%80%E5%B7%A7/%E5%A6%82%E4%BD%95%E5%9C%A8%E9%9D%A2%E8%AF%95%E4%B8%AD%E4%BB%8B%E7%BB%8D%E8%87%AA%E5%B7%B1%E7%9A%84%E9%A1%B9%E7%9B%AE%E7%BB%8F%E9%AA%8C.md)

[程序员如何写一份合格的简历](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%AC%94%E8%AF%95%E9%9D%A2%E8%AF%95%E6%8A%80%E5%B7%A7/%E5%A6%82%E4%BD%95%E5%86%99%E4%B8%80%E4%BB%BD%E5%90%88%E6%A0%BC%E7%9A%84%E7%AE%80%E5%8E%86.md)

## 面经总结
[嵌入式软件工程师的秋招之路](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%A7%8B%E6%8B%9B%E9%9D%A2%E7%BB%8F%E6%80%BB%E7%BB%93/%E5%B5%8C%E5%85%A5%E5%BC%8F%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E5%B8%88%E7%9A%84%E7%A7%8B%E6%8B%9B%E4%B9%8B%E8%B7%AF.md)

[嵌入式软件工程师面试经验总结](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%A7%8B%E6%8B%9B%E9%9D%A2%E7%BB%8F%E6%80%BB%E7%BB%93/%E8%81%94%E5%8F%91%E7%A7%91%E5%8D%8E%E4%B8%BA%E5%B0%8F%E7%B1%B3%E7%AD%8920%E5%AE%B6%E5%85%AC%E5%8F%B8%E9%9D%A2%E7%BB%8F%E6%80%BB%E7%BB%93.md)

[oppo和海康嵌入式软件工程师面经总结](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%A7%8B%E6%8B%9B%E9%9D%A2%E7%BB%8F%E6%80%BB%E7%BB%93/oppo%E5%92%8C%E6%B5%B7%E5%BA%B7%E5%B5%8C%E5%85%A5%E5%BC%8F%E8%BD%AF%E4%BB%B6%E5%B7%A5%E7%A8%8B%E5%B8%88%E9%9D%A2%E7%BB%8F%E5%88%86%E4%BA%AB.md)
## PDF获取方式

加我微信【LinuxDriverDev】，进技术交流群。

![](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%A7%8B%E6%8B%9B%E9%9D%A2%E7%BB%8F%E6%80%BB%E7%BB%93/%E4%B8%AA%E4%BA%BA%E4%BA%8C%E7%BB%B4%E7%A0%81-%E7%BE%8E%E5%8C%96.png)

关注公众号【嵌入式与Linux那些事】，回复【offer】即可**获取最新版**。

![](https://github.com/ZhongYi-LinuxDriverDev/Picture/blob/main/Wechat/%E5%85%AC%E4%BC%97%E5%8F%B7%E4%BA%8C%E7%BB%B4%E7%A0%81.png)

# 勘误

[勘误](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%9F%A5%E8%AF%86%E7%82%B9%E6%80%BB%E7%BB%93/%E5%8B%98%E8%AF%AF.md)

# 微信交流群干货分享
[日常群聊分享（持续更新中~）](https://github.com/ZhongYi-LinuxDriverDev/EmbeddedSoftwareEngineerInterview/blob/main/%E7%AC%94%E8%AF%95%E9%9D%A2%E8%AF%95%E6%8A%80%E5%B7%A7/%E5%BE%AE%E4%BF%A1%E7%BE%A4%E8%81%8A%E5%B9%B2%E8%B4%A7%E5%88%86%E4%BA%AB.md#%E6%89%AB%E7%A0%81%E5%8A%A0%E6%88%91%E5%BE%AE%E4%BF%A1)

# 榜上有名

[offer收割机]()

# 赞赏

创作不易，如果觉得这些资料对你有帮助，那就可以赞赏**一块钱**给我，金额不重要，**我想看到你的头像出现在我列表里**。

最后，祝愿各位老板，钱多多，offer多多，跳槽薪资double！

![](https://github.com/ZhongYi-LinuxDriverDev/Picture/blob/main/Wechat/%E5%BE%AE%E4%BF%A1%E6%94%B6%E6%AC%BE%E7%A0%81.png)

![](https://github.com/ZhongYi-LinuxDriverDev/Picture/blob/main/Wechat/%E6%94%AF%E4%BB%98%E5%AE%9D%E6%94%B6%E6%AC%BE%E7%A0%81.png)
