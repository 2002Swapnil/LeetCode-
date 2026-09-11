# 🟡 #0 - 103. Binary Tree Zigzag Level Order Traversal

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
                q.remove();
                TreeNode node = q.peek();
            for(int i=0;i<size;i++){
            List<Integer> res = new ArrayList<>(); 
            int size = q.size();
        while(!q.isEmpty()){

                res.add(node.val);
              
                if (node.left!=null) q.add(node.left);
                if (node.right!=null) q.add(node.right);
                
                
            }
            ans.add(res);
        }
        return ans;
    }

```

## Test Cases
```
Use Testcase
```

---
*Auto-synced by [LeetPush](https://github.com/yourusername/leetpush) 🚀*
