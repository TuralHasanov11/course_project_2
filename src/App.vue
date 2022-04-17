<template>
  <div id="app">
    <Navbar/>
     <div id="layoutSidenav">
            <Sidebar/>
            <div id="layoutSidenav_content">
                <main>
                    <router-view/>
                </main>
            </div>
        </div>
    
  </div>
</template>

<script>

import Navbar from '@/components/Navbar'
import Sidebar from '@/components/Sidebar'
export default {
  components: {
    Navbar,
    Sidebar,
  },

  
}
</script>