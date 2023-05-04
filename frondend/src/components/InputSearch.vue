<!-- <script>
export default {
    props: {
        modelValue: { type: String, default: "" },
    },
    emits: ["submit", "update:modelValue"],
    methods: {
        updateModelValue(e) {
            this.$emit("update:modelValue", e.target.value);
        },
        submit() {
            this.$emit("submit");
        },
    },
};
</script> -->
<template>
    <div class="search-box">
        <input type="text" placeholder="Tìm kiếm..." >
        <button><i class="fa fa-search"></i></button>
    </div>
</template>