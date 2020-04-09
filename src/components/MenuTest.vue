<template>
   <Menu mode="horizontal" theme="primary" >
        <MenuItem name="1" class="class1">
            <Icon type="ios-paper" />
            <span>内容管理</span>
        </MenuItem>
       <MenuItem name="2" class="class1">
           <Icon type="ios-people" />
           <span>用户管理</span>
       </MenuItem>
       <Submenu name="3" class="class1">
           <template slot="title" >
               <Icon type="ios-stats" />
               <span>统计分析</span>
           </template>
           <MenuItem name="3_1">
               全国地图分析
           </MenuItem>
           <MenuItem name="3_1">
               各省地图分析
           </MenuItem>
       </Submenu>
   </Menu>
</template>
<script>
    export default{
        name:"MenuTest",
        data(){
            return {

            }
        }
    }
</script>
<style scoped>
    .class1{
        padding: 0px 5px;
    }
</style>