<template>
    <div class="dashboard">
        <section>
            <div class="col1">
                <div class="profile">
                    <h5>{{userProfile.name}}</h5>
                    <p>{{userProfile.title}}</p>
                    <div class="create-post">
                        <p>Create Post</p>
                        <form @submit.prevent>
                            <textarea></textarea>
                            <button class="button">post</button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="col2">
                <div>
                    <p class="no-results">There are currently no posts</p>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
    export default {
        
    }
</script>