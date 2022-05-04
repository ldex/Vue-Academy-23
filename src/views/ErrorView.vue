<template>
<div>
    <h2>
    Error!
    </h2>
    <p>
        {{ message }}
    </p>
</div>
</template>

<script>
export default {
    props: ['message']
}
</script>