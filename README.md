# BuildingDesign
//                                                              </br>
//.ignore                                                       </br>
//中文版(忽略文件)                                               </br>
//                                                              </br>
//write by 2020/12/04                                           </br>
//                                                              </br>
/----序                                                            </br>
/建筑,建筑学                                                    </br>
/----第一章                                                         </br>
/古代建筑,现代建筑                                               </br>
/----第二章                                                         </br>
  
      Linux思维建筑基础设计(建筑物底端至顶端顺序),建筑基础的设计:
        砖混基础/水泥基础/中式竹基础/日式木基础
      两混基础，多混基础 
        砖水泥混合浇筑基础/钢筋水泥浇筑基础/中式泥地竹木混合基础/中式民建砖钢筋杂物等混合物水泥浇筑基础/
        中式构筑物水泥竹木基础/日式砖木混合基础
        ---
        古代多为四边形基础,异类多边形基础,
        现代多为多边形基础,起稳固抗震作用,极少数露出地面起美观效果,现代建筑以四边形为基础的依然存在,
           
     2D Linux---------->                粗略简写
               >>>>>>
               >>>>>基础(地基)
               >>>>楼板框架
               >>>屋顶结构
               >>管路系统
               >门窗
               >
               
     2D Linux---------->                粗略简写
               >
               >门窗
               >>管路系统
               >>>屋顶结构
               >>>>楼板框架
               >>>>>基础(地基)
               >>>>>>
               
             从细节上看每一栋房子,每一个家庭,房屋结构,以方方正正四边形为基础,
             人体结构及人体工程学划分横平竖直的辅助线,将人体与建筑分割又聚合在一起形成的房屋美学
             
             砖的大小240mm×115mm×53mm 
             砖块量的计算: 用平方算砖块/用砖块数算平方
             >>>>门的用量 横砖 竖砖 立砖 
             >>>立砖:(24块+砖块间的水泥厚度)*115mm-1个单位水泥厚度 / 24块*115mm+{24-1(顶部跟底部水泥冗量)}块*砖块间的水泥厚度
             >>根据:墙的用量-墙中的门砖块用量=实际墙体的用量
             >民建房屋高度3300mm/2600mm 
                 
                 未写完  
             
             >民建房屋高度3300mm/2600mm
             >>根据:墙的用量-墙中的门砖块用量=实际墙体的用量
             >>>立砖:(24块+砖块间的水泥厚度)*115mm-1个单位水泥厚度 / 24块*115mm+{24-1(顶部跟底部水泥冗量)}块*砖块间的水泥厚度
             >>>>门的用量 横砖 竖砖 立砖 
             
             未写完  
               
             从建筑学角度看多边形分割 456789 9+ 多边形
             
              0 0 0
             0  0  0  0 四边形
             0 0 0 0 1 一点两边 构成五边形
             0 0 0 0 1 1 两点三边 构成六边形 0 0 0 0 0 1 / 0 0 0 0 1 0 
             0 0 0 0 1 1 1 三点四边 构成七边形 0 0 0 0 0 1 0 / 0 0 0 0 1 0 0 / 0 0 0 0 1 1 0 
             ...
             
                未写完
               
