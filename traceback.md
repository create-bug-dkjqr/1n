def backward():
    
        if (回朔点）：# 这条路走到底的条件。也是递归出口
                保存该结果
                        return   
                            
                                else:
                                        for route in all_route_set :  逐步选择当前节点下的所有可能route
                                                    
                                                                if 剪枝条件：
                                                                                剪枝前的操作
                                                                                                return   #不继续往下走了，退回上层，换个路再走
                                                                                                            
                                                                                                                        else：#当前路径可能是条可行路径
                                                                                                                                    
                                                                                                                                                    保存当前数据  #向下走之前要记住已经走过这个节点了。例如push当前节点
                                                                                                                                                            
                                                                                                                                                                            self.backward() #递归发生，继续向下走一步了。
                                                                                                                                                                                            
                                                                                                                                                                                                            回朔清理     # 该节点下的所有路径都走完了，清理堆栈，准备下一个递归。例如弹出当前节点
                                                                                                                                                                                                            
                                                                                                                                                                                                            作者：allen-238
                                                                                                                                                                                                            链接：https://leetcode-cn.com/problems/combination-sum/solution/xiang-xi-hui-shuo-fa-jiang-jie-he-hui-shuo-mo-ban-/
                                                                                                                                                                                                            来源：力扣（LeetCode）
                                                                                                                                                                                                            著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。)
