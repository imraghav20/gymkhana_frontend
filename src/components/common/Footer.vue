<template lang="pug">
  div
    section
      v-card.elevation-0(color="blue darken-1 white--text" flat tile)
        v-row(style="{background: #000000}").justify-center
          v-col(cols="12" md="6").text-center
            v-layout(row)
              v-container
                span ABOUT US
                p Student Gymkhana IITJ
          v-col(cols="12" md="6").text-center
            v-layout(row)
              v-container(class="white--text")
                p QUICK LINKS
                p
                  a(href="http://iitj.ac.in" class="white--text" style="text-decoration: none;") IIT Jodhpur
                p Contact Us
                p
                  a(href="http://iitj.ac.in/academics/index.php?id=academic_calendar" class="white--text" style="text-decoration: none;") Academic Calender
    v-footer(color="blue darken-2 white--text").text-center.justify-center.align-center
      h4.font-weight-regular © {{new Date().getFullYear() }} COPYRIGHT  | Made with
      v-icon(color="red").pa-1 mdi-heart
      h4.font-weight-regular by Students' Gymkhana WebD Team
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style scoped>
section {
  overflow-x: hidden;
}
</style>
