<template>
    <header class="f-header">
        <div class="narrow-container">
            <div class="row no-collapse align-items-center">
                <div class="col">
                    <router-link to="/" class="logo" :aria-label="$t('view_home.back_to_home')">
                        <img
                            style="height: 80px !important; width: 80px;"
                            src="https://anbswap.com/logo.png"
                            alt="logo"
                            width="80"
                            height="80"
                        />
                    </router-link>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
/**
 * Renderes header and takes care of navigation.
 */
export default {
    components: {},
};
</script>

<style lang="scss">
@import 'style';
</style>
