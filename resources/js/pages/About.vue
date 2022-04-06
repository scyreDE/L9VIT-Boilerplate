<template>
    <div>
           <h1 class="text-3xl font-bold underline">
     Another Inertia linked page
  </h1>

        <Link href="/">Go to Home</Link>
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