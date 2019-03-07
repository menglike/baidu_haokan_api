# baidu_haokan_api
百度好看短视频一网打尽

# 短视频分类： 影视 搞笑 音乐 小品 娱乐 社会 生活 猎奇 游戏 呆萌

参数名称	类型	 默认值	示例值	必须	描述
type	  String	无	    1033  是	  视频类型,只能为 [1033,1060,1059,1058,1062,1061,1063,1066,1064,1067,1065]中的一个 1033=>推荐 1060=>影视 1059=>搞笑 1058=>音乐 1062=>小品 1061=>娱乐 1063=>社会 1066=>生活 1064=>猎奇 1067=>游戏 1065=>呆萌
cate	  String	list	 list  是	 请求类型,只能为"list"
page	  String	1	     1     否	 当前页数，一页10条

返回JSON格式
{
  "showapi_res_error": "",
  "showapi_res_id": "717470c7022d48e1a011e03a4516fd72",
  "showapi_res_code": 0,
  "showapi_res_body": {
    "0": {
      "source": "小乔神技能",
      "tag": "生活",
      "title": "泡打粉、小苏打和酵母粉它们有什么区别？看完别再用错了，快看看",
      "avatar": "//publish-pic-cpu.baidu.com/537ce9ec-ff0d-4a45-b728-bc6322cf8eec.png",
      "brief": "泡打粉、小苏打和酵母粉它们有什么区别？看完别再用错了，快看看！生活小技巧，生活小窍门，生活小妙招，生活小技能。",
      "url": "https://vd3.bdstatic.com/mda-im5cusaf4mpgg7kh/mda-im5cusaf4mpgg7kh.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 80,
      "playbackCount": 50885,
      "thumbUrl": "//publish-pic-cpu.baidu.com/1e9d9c6c-1ee1-4c97-b16f-d52fbc66d759.jpeg@w_770,h_432"
    },
    "1": {
      "source": "格斗世界官方",
      "tag": "体育",
      "title": "日本拳手出场嘚瑟扭屁股挑衅，中国跤王暴揍绞杀观众看不惯扔水瓶",
      "avatar": "//publish-pic-cpu.baidu.com/7bf8861a-3a04-4fb7-b446-a09bce1cf808.png",
      "brief": "日本拳手出场嘚瑟扭屁股挑衅，遭中国跤王暴揍绞杀观众看不惯扔水瓶、lebron",
      "url": "https://vd3.bdstatic.com/mda-imvpa53ufpwtiqb2/mda-imvpa53ufpwtiqb2.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 187,
      "playbackCount": 44957,
      "thumbUrl": "//publish-pic-cpu.baidu.com/5173a099-1e81-4b4e-b3e6-c82734f440f1.jpeg@w_786,h_441"
    },
    "2": {
      "source": "动漫欢乐圈",
      "tag": "旅游",
      "title": "非洲吃人部落，这些人看起来好恐怖啊！",
      "avatar": "//publish-pic-cpu.baidu.com/38278d58-9b0f-4290-93de-085936531387.png",
      "brief": "非洲吃人部落，这些人看起来好恐怖啊！",
      "url": "https://vd3.bdstatic.com/mda-imhpxuuemqvrvsm9/mda-imhpxuuemqvrvsm9.mp4?playlist=%5B%22hd%22%5D",
      "duration": 12,
      "playbackCount": 70027,
      "thumbUrl": "//publish-pic-cpu.baidu.com/cf826245-1f54-4967-82d8-b16acb773dde.jpeg@w_660,h_370"
    },
    "3": {
      "source": "素手映红梅",
      "tag": "财经",
      "title": "听过马云爸爸唱歌吗？短短的一句，就能看出台下没少下功夫啊",
      "avatar": "//publish-pic-cpu.baidu.com/c16a5fa9-92cc-469e-8116-67fe85c2a0c6.png",
      "brief": "听过马云爸爸唱歌吗？短短的一句，就能看出台下没少下功夫啊",
      "url": "https://vd3.bdstatic.com/mda-im6m7i0uhidkreek/mda-im6m7i0uhidkreek.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 15,
      "playbackCount": 37794,
      "thumbUrl": "//publish-pic-cpu.baidu.com/7c0f2679-dd57-489f-8d1d-86c67154d492.jpeg@w_660,h_370"
    },
    "4": {
      "source": "老叶汽车工作室",
      "tag": "表演",
      "title": "诡异女孩参加达人秀把评委都吓得离开座位",
      "avatar": "//publish-pic-cpu.baidu.com/55b9b7db-7032-4198-acdd-1e4472a6b9de.jpeg",
      "brief": "诡异女孩参加达人秀把评委都吓得离开座位",
      "url": "https://vd3.bdstatic.com/mda-ijnp4qhtdkn6f075/mda-ijnp4qhtdkn6f075.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 203,
      "playbackCount": 124738,
      "thumbUrl": "//publish-pic-cpu.baidu.com/c0c92525-13ed-47c0-880a-3f2068e21010.jpeg@w_1280,h_718"
    },
    "5": {
      "source": "娱乐美亚",
      "tag": "萌宠",
      "title": "这对双胞胎火了，两人打个架都在围观，看完不许笑！",
      "avatar": "//publish-pic-cpu.baidu.com/7da3e8ae-c6c1-4feb-9953-cc7f2a58685a.jpeg",
      "brief": "这对双胞胎火了，两人打个架都在围观，看完不许笑！",
      "url": "https://vd3.bdstatic.com/mda-im6ry4epe5qix4de/mda-im6ry4epe5qix4de.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 11,
      "playbackCount": 107695,
      "thumbUrl": "//publish-pic-cpu.baidu.com/85c46cd1-c923-4aa4-864d-8c4ae4f83221.jpeg@w_720,h_404"
    },
    "6": {
      "source": "晨晨旅游说",
      "tag": "旅游",
      "title": "中国地理位置最好的省会，广州和西安败给了它，是你的家乡吗？",
      "avatar": "//publish-pic-cpu.baidu.com/0bbd608f-6c95-4a6b-8358-6a1c7c4957e2.jpeg",
      "brief": "中国地理位置最好的省会，广州和西安败给了它，是你的家乡吗？",
      "url": "https://vd3.bdstatic.com/mda-imjxm02cjs8c17x5/mda-imjxm02cjs8c17x5.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 87,
      "playbackCount": 4202,
      "thumbUrl": "//publish-pic-cpu.baidu.com/1a906c6e-0599-4225-a70b-7aba4d9956fe.jpeg@w_799,h_448"
    },
    "7": {
      "source": "小雀幸儿",
      "tag": "财经",
      "title": "王健林再次预测三四线城市房价，句句实话，网友：咋不早说！",
      "avatar": "//publish-pic-cpu.baidu.com/848dd415-797f-4e19-9f07-0e6a0b5cb5bf.jpeg",
      "brief": "王健林再次预测三四线城市房价，句句实话，网友：咋不早说！",
      "url": "https://vd3.bdstatic.com/mda-imregnww86ky5emm/mda-imregnww86ky5emm.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 55,
      "playbackCount": 61506,
      "thumbUrl": "//publish-pic-cpu.baidu.com/fecde7e7-f045-40a2-aac1-d607514b2919.jpeg@w_864,h_486"
    },
    "8": {
      "source": "一米五的小个子",
      "tag": "表演",
      "title": "鸡蛋穿瓶子魔术，原来是这样做到的，我也学会了",
      "avatar": "//publish-pic-cpu.baidu.com/b46df9c5-0692-4651-9b46-95c3b466dce2.jpeg",
      "brief": "鸡蛋穿瓶子魔术，原来是这样做到的，我也学会了",
      "url": "https://vd3.bdstatic.com/mda-ihurkurc6e36hie3/mda-ihurkurc6e36hie3.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 18,
      "playbackCount": 38749,
      "thumbUrl": "//publish-pic-cpu.baidu.com/91e08a6f-07b5-45fb-8398-82332e8602d1.jpeg@w_692,h_388"
    },
    "9": {
      "source": "牵着兔子去散步",
      "tag": "萌宠",
      "title": "主人要把小狗炖了，不料拉布拉多叼着盆想吃狗肉，看完不许笑！",
      "avatar": "//publish-pic-cpu.baidu.com/482c1c2c-6b98-4969-8b34-33fe21540642.png",
      "brief": "主人要把小狗炖了，不料拉布拉多叼着盆想吃狗肉，看完不许笑！",
      "url": "https://vd3.bdstatic.com/mda-im6cdp2mja2ndksn/mda-im6cdp2mja2ndksn.mp4?playlist=%5B%22hd%22%2C%22sc%22%5D",
      "duration": 22,
      "playbackCount": 20998,
      "thumbUrl": "//publish-pic-cpu.baidu.com/96bf4af6-5338-42e4-acaa-83f0dd91a143.jpeg@w_1280,h_718"
    },
    "ret_code": 0
  }
}
