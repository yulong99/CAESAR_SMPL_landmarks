# 创建映射来修正多个名称/错误拼写/等标志点名称
# 有些名称保持不变
CAESAR数据集中标记文件数据格式为
# 示例的标记点行
      # 1   0   1   43.22   19.77  -38.43  522.00 Sellion
      # 坐标应该是
      # 0.01977, -0.03843, 0.522
# 表示最后三个浮点数是坐标
CAESAR_LANDMARK_MAPPING =  {
     '10th Rib Midspine': '第10肋骨脊柱中点',
     'AUX LAND': '辅助标志点',
     'Butt Block': '臀部标志点',
     'Cervical': '颈椎', # 修正
     'Cervicale': '颈椎', 
     'Crotch': '胯部',
     'Lt. 10th Rib': '左侧第10肋骨',
     'Lt. ASIS': '左侧髂前上棘',
     'Lt. Acromio': '左侧肩峰', # 修正
     'Lt. Acromion': '左侧肩峰',
     'Lt. Axilla, An': '左侧腋窝前', # 修正
     'Lt. Axilla, Ant': '左侧腋窝前', # 修正
     'Lt. Axilla, Post': '左侧腋窝后', # 修正
     'Lt. Axilla, Post.': '左侧腋窝后',
     'Lt. Calcaneous, Post.': '左侧跟骨后',
     'Lt. Clavicale': '左侧锁骨',
     'Lt. Dactylion': '左侧指尖',
     'Lt. Digit II': '左侧第II指',
     'Lt. Femoral Lateral Epicn': '左侧股骨外侧髁',
     'Lt. Femoral Lateral Epicn ': '左侧股骨外侧髁', # 修正
     'Lt. Femoral Medial Epicn': '左侧股骨内侧髁',
     'Lt. Gonion': '左侧下颌角',
     'Lt. Humeral Lateral Epicn': '左侧肱骨外侧髁',
     'Lt. Humeral Medial Epicn': '左侧肱骨内侧髁',
     'Lt. Iliocristale': '左侧髂嵴',
     'Lt. Infraorbitale': '左侧眶下点',
     'Lt. Knee Crease': '左侧膝盖皱褶',
     'Lt. Lateral Malleolus': '左侧外踝',
     'Lt. Medial Malleolu': '左侧内踝', # 修正
     'Lt. Medial Malleolus': '左侧内踝',
     'Lt. Metacarpal-Phal. II': '左侧掌指关节 II', # 修正
     'Lt. Metacarpal-Phal. V': '左侧掌指关节 V', # 修正
     'Lt. Metatarsal-Phal. I': '左侧跖趾关节 I', # 修正
     'Lt. Metatarsal-Phal. V': '左侧跖趾关节 V', # 修正
     'Lt. Olecranon': '左侧鹰嘴',
     'Lt. PSIS': '左侧髂后上棘',
     'Lt. Radial Styloid': '左侧桡骨茎突',
     'Lt. Radiale': '左侧桡骨',
     'Lt. Sphyrio': '左侧舟状骨', # 修正
     'Lt. Sphyrion': '左侧舟状骨',
     'Lt. Thelion/Bustpoin': '左侧乳头点', # 修正
     'Lt. Thelion/Bustpoint': '左侧乳头点',
     'Lt. Tragion': '左侧耳屏',
     'Lt. Trochanterion': '左侧转子点',
     'Lt. Ulnar Styloid': '左侧尺骨茎突',
     'Nuchale': '颈背点',
     'Rt. 10th Rib': '右侧第10肋骨',
     'Rt. ASIS': '右侧髂前上棘',
     'Rt. Acromio': '右侧肩峰', # 修正
     'Rt. Acromion': '右侧肩峰',
     'Rt. Axilla, An': '右侧腋窝前', # 修正
     'Rt. Axilla, Ant': '右侧腋窝前', # 修正
     'Rt. Axilla, Post': '右侧腋窝后', # 修正
     'Rt. Axilla, Post.': '右侧腋窝后',
     'Rt. Calcaneous, Post.': '右侧跟骨后',
     'Rt. Clavicale': '右侧锁骨',
     'Rt. Dactylion': '右侧指尖',
     'Rt. Digit II': '右侧第II指',
     'Rt. Femoral Lateral Epicn': '右侧股骨外侧髁',
     'Rt. Femoral Lateral Epicn ': '右侧股骨外侧髁', # 修正
     'Rt. Femoral Medial Epic': '右侧股骨内侧髁', # 修正
     'Rt. Femoral Medial Epicn': '右侧股骨内侧髁',
     'Rt. Gonion': '右侧下颌角',
     'Rt. Humeral Lateral Epicn': '右侧肱骨外侧髁',
     'Rt. Humeral Medial Epicn': '右侧肱骨内侧髁',
     'Rt. Iliocristale': '右侧髂嵴',
     'Rt. Infraorbitale': '右侧眶下点',
     'Rt. Knee Creas': '右侧膝盖皱褶', # 修正
     'Rt. Knee Crease': '右侧膝盖皱褶',
     'Rt. Lateral Malleolus': '右侧外踝',
     'Rt. Medial Malleolu': '右侧内踝', # 修正
     'Rt. Medial Malleolus': '右侧内踝',
     'Rt. Metacarpal Phal. II': '右侧掌指关节 II',
     'Rt. Metacarpal-Phal. V': '右侧掌指关节 V', # 修正
     'Rt. Metatarsal-Phal. I': '右侧跖趾关节 I', # 修正
     'Rt. Metatarsal-Phal. V': '右侧跖趾关节 V', # 修正
     'Rt. Olecranon': '右侧鹰嘴',
     'Rt. PSIS': '右侧髂后上棘',
     'Rt. Radial Styloid': '右侧桡骨茎突',
     'Rt. Radiale': '右侧桡骨',
     'Rt. Sphyrio': '右侧舟状骨', # 修正
     'Rt. Sphyrion': '右侧舟状骨',
     'Rt. Thelion/Bustpoin': '右侧乳头点', # 修正
     'Rt. Thelion/Bustpoint': '右侧乳头点',
     'Rt. Tragion': '右侧耳屏',
     'Rt. Trochanterion': '右侧转子点',
     'Rt. Ulnar Styloid': '右侧尺骨茎突',
     'Sellion': '鼻根点',
     'Substernale': '胸骨下缘',
     'Supramenton': '颏上点',
     'Suprasternale': '胸骨上缘',
     'Waist, Preferred, Post.': '腰部偏后位置'
}

SMPL_INDEX_LANDMARKS = {
    '10th Rib Midspine': 3024,  # 第10肋骨中脊
    'Cervicale': 829,  # 颈椎
    'Crotch': 1353,  # 胯部
    'Lt. 10th Rib': 1481,  # 左侧第10肋骨
    'Lt. ASIS': 3157,  # 左侧前上髂棘
    'Lt. Acromion': 1862,  # 左侧肩峰
    'Lt. Axilla, Ant.': 1871,  # 左侧腋前
    'Lt. Axilla, Post.': 2991,  # 左侧腋后
    'Lt. Calcaneous, Post.': 3387,  # 左侧跟骨后
    'Lt. Clavicale': 1300,  # 左侧锁骨
    'Lt. Dactylion': 2446,  # 左手指尖
    'Lt. Digit II': 3222,  # 左侧第二指
    'Lt. Femoral Lateral Epicn': 1008,  # 左侧股骨外上髁
    'Lt. Femoral Medial Epicn': 1016,  # 左侧股骨内上髁
    'Lt. Gonion': 148,  # 左侧下颌角
    'Lt. Humeral Lateral Epicn': 1621,  # 左侧肱骨外上髁
    'Lt. Humeral Medial Epicn': 1661,  # 左侧肱骨内上髁
    'Lt. Iliocristale': 677,  # 左侧髂嵴
    'Lt. Infraorbitale': 341,  # 左侧眶下点
    'Lt. Knee Crease': 1050,  # 左膝折痕
    'Lt. Lateral Malleolus': 3327,  # 左侧外踝
    'Lt. Medial Malleolus': 3432,  # 左侧内踝
    'Lt. Metacarpal Phal. II': 2258,  # 左侧第二掌骨
    'Lt. Metacarpal Phal. V': 2082,  # 左侧第五掌骨
    'Lt. Metatarsal Phal. I': 3294,  # 左侧第一跖骨
    'Lt. Metatarsal Phal. V': 3348,  # 左侧第五跖骨
    'Lt. Olecranon': 1736,  # 左侧鹰嘴
    'Lt. PSIS': 3097,  # 左侧后上髂棘
    'Lt. Radial Styloid': 2112,  # 左侧桡骨茎突
    'Lt. Radiale': 1700,  # 左侧桡骨头
    'Lt. Sphyrion': 3417,  # 左侧足舟骨
    'Lt. Thelion/Bustpoint': 598,  # 左乳点
    'Lt. Tragion': 448,  # 左侧耳屏
    'Lt. Trochanterion': 808,  # 左侧大转子
    'Lt. Ulnar Styloid': 2108,  # 左侧尺骨茎突
    'Nuchale': 445,  # 枕骨下点
    'Rt. 10th Rib': 4953,  # 右侧第10肋骨
    'Rt. ASIS': 6573,  # 右侧前上髂棘
    'Rt. Acromion': 5342,  # 右侧肩峰
    'Rt. Axilla, Ant.': 5332,  # 右侧腋前
    'Rt. Axilla, Post.': 6450,  # 右侧腋后
    'Rt. Calcaneous, Post.': 6786,  # 右侧跟骨后
    'Rt. Clavicale': 4782,  # 右侧锁骨
    'Rt. Dactylion': 5907,  # 右手指尖
    'Rt. Digit II': 6620,  # 右侧第二指
    'Rt. Femoral Lateral Epicn': 4493,  # 右侧股骨外上髁
    'Rt. Femoral Medial Epicn': 4500,  # 右侧股骨内上髁
    'Rt. Gonion': 3661,  # 右侧下颌角
    'Rt. Humeral Lateral Epicn': 5090,  # 右侧肱骨外上髁
    'Rt. Humeral Medial Epicn': 5131,  # 右侧肱骨内上髁
    'Rt. Iliocristale': 4165,  # 右侧髂嵴
    'Rt. Infraorbitale': 3847,  # 右侧眶下点
    'Rt. Knee Crease': 4535,  # 右膝折痕
    'Rt. Lateral Malleolus': 6728,  # 右侧外踝
    'Rt. Medial Malleolus': 6832,  # 右侧内踝
    'Rt. Metacarpal Phal. II': 5578,  # 右侧第二掌骨
    'Rt. Metacarpal Phal. V': 5545,  # 右侧第五掌骨
    'Rt. Metatarsal Phal. I': 6694,  # 右侧第一跖骨
    'Rt. Metatarsal Phal. V': 6715,  # 右侧第五跖骨
    'Rt. Olecranon': 5205,  # 右侧鹰嘴
    'Rt. PSIS': 6521,  # 右侧后上髂棘
    'Rt. Radial Styloid': 5534,  # 右侧桡骨茎突
    'Rt. Radiale': 5170,  # 右侧桡骨头
    'Rt. Sphyrion': 6817,  # 右侧足舟骨
    'Rt. Thelion/Bustpoint': 4086,  # 右乳点
    'Rt. Tragion': 3941,  # 右侧耳屏
    'Rt. Trochanterion': 4310,  # 右侧大转子
    'Rt. Ulnar Styloid': 5520,  # 右侧尺骨茎突
    'Sellion': 410,  # 鼻根点
    'Substernale': 3079,  # 胸骨下点
    'Supramenton': 3051,  # 颏上点
    'Suprasternale': 3171,  # 胸骨上点
    'Waist, Preferred, Post.': 3021  # 腰部后面
}
