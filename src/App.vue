  <template>
    <div id="app" class="flex bg-gray-900 text-white min-h-screen" >
        <sidebar-navigation />
      <div class="w-full">
        <div class="container mx-auto ">
          <router-view/>

        </div>

      </div>
  </div>
</template>


<script>
import SidebarNavigation from '@/components/SidebarNavigation'


export default {
  components:{
    SidebarNavigation
  }

}
</script>

<style src="./css/main.css"> </style>