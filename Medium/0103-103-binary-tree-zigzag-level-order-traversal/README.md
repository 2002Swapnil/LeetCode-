# 🟡 #103 - 103. Binary Tree Zigzag Level Order Traversal

## Problem Info
| Field | Value |
|-------|-------|
| **Difficulty** | Medium |
| **Topics** | Tree, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Solved** | 9/12/2026 |

## Solution
```txt
                if(level%2==1){
                    if (node.right!=null) q.add(node.right);
                    if (node.left!=null)q.add(node.left);
                }else{
                
            }
            ans.add(res);
                res.add(node.val);
                q.remove();
                TreeNode node = q.peek();
            for(int i=0;i<size;i++){
            List<Integer> res = new ArrayList<>(); 
                    if (node.left!=null) q.add(node.left);
                }
                    if (node.right!=null) q.add(node.right);
            int size = q.size();
        while(!q.isEmpty()){
            level++;

```



---
*Auto-synced by [LeetPush](https://github.com/yourusername/leetpush) 🚀*
