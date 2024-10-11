<script>
    import { MessageSquare } from 'lucide-svelte';
    import { Share } from 'lucide-svelte';
    import { ArrowBigUp } from 'lucide-svelte';
    import { ArrowBigDown } from 'lucide-svelte';
    </script>
    
    <div class="w-full mx-auto flex p-5 gap-x-8 h-full">
	<div class="w-1/4 bg-neutral-50 rounded-xl">
		<h1 class='card-title'>Subscriptions</h1>
        <div>
            <ul>
                <li class='subscriptions'><a>Subscription</a></li>
                <li class='subscriptions'><a>Subscription</a></li>
                <li class='subscriptions'><a>Subscription</a></li>
                <li class='subscriptions'><a>Subscription</a></li>
                <li class='subscriptions'><a>Subscription</a></li>
                <li class='subscriptions'><a>Subscription</a></li>
            </ul>
            
        </div>
	</div>
	<div class="w-3/4 bg-neutral-50 rounded-xl">
		<h1 class='card-title'>Feed</h1>
        <div>
            <div class='post-feed'>
                <h3><span>Forum</span> - <span>Time</span></h3>
                <h2 class='pl-0.5'>Post title</h2>
                <p class='pl-0.5'>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nobis sint pariatur odio vel commodi, libero aperiam corrupti. Earum ab deserunt iusto architecto beatae nemo veniam cupiditate, libero accusamus commodi reiciendis.</p>
                <div class='flex gap-x-2 pt-1'>
                    <ArrowBigUp class='post-icon'/>
                    <ArrowBigDown class='post-icon'/>
                    <MessageSquare class='post-icon'/>
                    <Share class='post-icon'/>
                </div>
            </div>
        </div>
	</div>
	<!-- <div class="w-1/6">
		<h1 class='card-title'>Hisotry</h1>
	</div> -->
</div>

<style>
    .card-title{
        @apply font-semibold text-center text-2xl py-4
    }

    .subscriptions{
        @apply font-medium text-lg px-3 py-0.5 gap-y-2 rounded-xl hover:bg-neutral-100 mx-2
    }

    .post-feed {
        @apply bg-neutral-200 m-4 p-4 rounded-xl; 
    }

    .post-feed h2 {
        @apply text-2xl font-semibold;
    }

    .post-feed h3 {
        @apply text-base font-normal;
    }

    .post-feed h3 span {
        @apply bg-neutral-300 px-2 py-0.5 rounded-full font-semibold;
    }

    .post-icon {
        @apply h-5 w-5 p-1 bg-neutral-600 rounded-full;
    }
</style>