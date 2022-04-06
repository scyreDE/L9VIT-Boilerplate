<template>
    <div>
         <h1 class="text-3xl font-bold underline">
     Welcome to the L9VIT Stack!
  </h1>

        <Link href="/about-us">Go to About Us</Link>
    </div>
</template>

<script>
import { Link } from "@inertiajs/inertia-vue3";
export default {
    components: {
        Link,
    },
};
</script>