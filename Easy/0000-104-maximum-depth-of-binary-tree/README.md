# 🟢 #0 - 104. Maximum Depth of Binary Tree

## Problem Info
| Field | Value |
|-------|-------|
| **Difficulty** | Easy |
| **Topics** | Tree, Depth-First Search, Breadth-First Search, Binary Tree |
| **Language** | Unknown |
| **Runtime** | N/A |
| **Memory** | N/A |
| **Solved** | 9/12/2026 |

## Solution
```txt
        Queue<TreeNode> q = new LinkedList<>();
        q.add(root);
        while(!q.isEmpty()){
            int size = q.size();
            for(int i=0;i<size;i++){
                TreeNode node = q.remove();
            }
            level++;
        }
    }
                if (node.left!=null) q.add(node.left);
                if (node.right!=null) q.add(node.right);
        int level = 0;
        return level;
}

```



---
*Auto-synced by [LeetPush](https://github.com/yourusername/leetpush) 🚀*
