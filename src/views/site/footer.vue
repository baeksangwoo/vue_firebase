<template>
    <v-footer
            color="primary"
            dark
            absolute>
            <v-spacer></v-spacer>
            <div>&copy; {{ new Date().getFullYear() + ' ' + footer}}</div>
    </v-footer>
</template>

<script>
export default {
  props: ['footer']
}
</script>
