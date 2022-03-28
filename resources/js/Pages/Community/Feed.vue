<template>

<community-layout>
	
<div class="mcontainer"> <!-- Start -->

                <div class="flex justify-between relative md:mb-4 mb-3">
                    <div class="flex-1">
                        <h2 class="text-2xl font-semibold"> Upload your content </h2>
                    </div>
                </div>

                <br>  

                <div class="divide-y">


                    <div class="flex md:space-x-6 space-x-4 md:py-5 py-3 relative">
                        
                    </div> 

                </div> 
        
            </div> <!-- End -->
	
</community-layout>	
            
	
</template>


<script>
    import { defineComponent } from 'vue'
    import CommunityLayout from '@/Layouts/CommunityLayout.vue'

    export default defineComponent({
        components: {
            CommunityLayout,
        },
    })
</script>
