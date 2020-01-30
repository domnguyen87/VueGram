<template>
    <header>
        <section>
            <div class="col1">
                <router-link to="dashboard"><h3>Vuegram</h3></router-link>
                <ul class='inline'>
                    <li><router-link to="dashboard">Dashboard</router-link></li>
                    <li><router-link to="settings">Settings</router-link></li>
                    <li><a @click="logout">Logout</li>
                </ul>
            </div>
        </section>
    </header>
</template>

<script>
    export default {
        
    }
</script>