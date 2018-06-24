<template>
    <div>
    <Sidebar main-title="Sidebar" sub-title="Example" :routes="routes"/>
    </div>
</template>

<script>
    import Router from '../../router'
    import Sidebar from 'vue-sidebar-component'
export default {
    name: 'Header',
    data : function () {
        return{
            routes : Router.routes
        }
    },
    components:{Sidebar: Sidebar}
}

</script>