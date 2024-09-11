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
            <div class='bg-neutral-100'>
                <h3>Forum - Time</h3>
                <h2>Post title</h2>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nobis sint pariatur odio vel commodi, libero aperiam corrupti. Earum ab deserunt iusto architecto beatae nemo veniam cupiditate, libero accusamus commodi reiciendis.</p>
                <div class='flex'>
                    <a>Upvote/Downvote</a>
                    <p>Comments</p>
                    <p>views</p>
                    <button>Share</button>
                </div>
            </div>
        </div>
	</div>
	<div class="w-1/6">
		<h1 class='card-title'>Hisotry</h1>
	</div>
</div>

<style>
    .card-title{
        @apply font-semibold text-center text-2xl
    }

    .subscriptions{
        @apply font-medium text-lg px-2 py-0.5 gap-y-2 rounded-xl hover:bg-neutral-100
    }
</style>