<template>
    <div>
        <div class="navbar bg-slate-700 flex justify-between">
            <a class="btn btn-ghost normal-case text-xl">ASC</a>
            <router-link to="/login">
                <a class="btn btn-error normal-case text-lg">Login</a>
            </router-link>
        </div>
    </div>
</template>
<script>
import { RouterLink } from 'vue-router';
export default {
    name: 'Header',
}
</script>