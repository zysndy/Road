### 组件destoryed触发
- 当页面上仅有一个组件时,组件节点从页面上消失时,触发destoryed
- 当页面上有个多个相同组件,某一个节点从页面上消失时,不会触发destoryed,组件会重复使用
- 当页面上有多个相同组件需要触发destoryed，此时应该给组件加上对应的key值，确保组件的唯一性