<template>
  <div class="robocontainer">
    <div class="robolayer robohash-007-orange-face-10"></div>
    <div class="robolayer robohash-007-orange-mouth-09"></div>
    <div class="robolayer robohash-007-orange-eyes-07"></div>
    <div class="robolayer robohash-007-orange-accessory-06"></div>

    <div class="robolayer robohash-007-orange-body-02"></div>
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class Robohash extends Vue {
}
</script>
<style scoped lang="scss">
@import '../assets/sprites.scss';
.robocontainer {
    position: relative;
}
.robolayer {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
}
/* eslint-disable */
.robohash-000-blue-accessory-02, .robohash-000-blue-body-10, .robohash-000-blue-eyes-07, .robohash-000-blue-face-07, .robohash-000-blue-mouth-10,
.robohash-000-brown-accessory-07, .robohash-000-brown-body-06, .robohash-000-brown-eyes-05, .robohash-000-brown-face-09, .robohash-000-brown-mouth-02,
.robohash-000-green-accessory-07, .robohash-000-green-body-08, .robohash-000-green-eyes-05, .robohash-000-green-face-10, .robohash-000-green-mouth-08,
.robohash-000-grey-accessory-01, .robohash-000-grey-body-03, .robohash-000-grey-eyes-06, .robohash-000-grey-face-10, .robohash-000-grey-mouth-08,
.robohash-000-orange-accessory-05, .robohash-000-orange-body-07, .robohash-000-orange-eyes-05, .robohash-000-orange-face-01, .robohash-000-orange-mouth-07,
.robohash-000-pink-accessory-07, .robohash-000-pink-body-01, .robohash-000-pink-eyes-05, .robohash-000-pink-face-07, .robohash-000-pink-mouth-03,
.robohash-000-purple-accessory-04, .robohash-000-purple-body-10, .robohash-000-purple-eyes-09, .robohash-000-purple-face-05, .robohash-000-purple-mouth-01,
.robohash-000-red-accessory-03, .robohash-000-red-body-09, .robohash-000-red-eyes-07, .robohash-000-red-face-08, .robohash-000-red-mouth-07,
.robohash-000-white-accessory-04, .robohash-000-white-body-01, .robohash-000-white-eyes-07, .robohash-000-white-face-01, .robohash-000-white-mouth-04,
.robohash-000-yellow-accessory-07, .robohash-000-yellow-body-04, .robohash-000-yellow-eyes-10, .robohash-000-yellow-face-02, .robohash-000-yellow-mouth-03,
.robohash-001-blue-accessory-01, .robohash-001-blue-body-09, .robohash-001-blue-eyes-09, .robohash-001-blue-face-03, .robohash-001-blue-mouth-07,
.robohash-001-brown-accessory-08, .robohash-001-brown-body-08, .robohash-001-brown-eyes-06, .robohash-001-brown-face-02, .robohash-001-brown-mouth-01,
.robohash-001-green-accessory-03, .robohash-001-green-body-01, .robohash-001-green-eyes-07, .robohash-001-green-face-09, .robohash-001-green-mouth-04,
.robohash-001-grey-accessory-03, .robohash-001-grey-body-09, .robohash-001-grey-eyes-05, .robohash-001-grey-face-03, .robohash-001-grey-mouth-03,
.robohash-001-orange-accessory-03, .robohash-001-orange-body-05, .robohash-001-orange-eyes-01, .robohash-001-orange-face-03, .robohash-001-orange-mouth-01,
.robohash-001-pink-accessory-02, .robohash-001-pink-body-03, .robohash-001-pink-eyes-01, .robohash-001-pink-face-02, .robohash-001-pink-mouth-02,
.robohash-001-purple-accessory-02, .robohash-001-purple-body-04, .robohash-001-purple-eyes-08, .robohash-001-purple-face-01, .robohash-001-purple-mouth-10,
.robohash-001-red-accessory-09, .robohash-001-red-body-01, .robohash-001-red-eyes-02, .robohash-001-red-face-06, .robohash-001-red-mouth-05,
.robohash-001-white-accessory-06, .robohash-001-white-body-08, .robohash-001-white-eyes-10, .robohash-001-white-face-07, .robohash-001-white-mouth-08,
.robohash-001-yellow-accessory-09, .robohash-001-yellow-body-06, .robohash-001-yellow-eyes-09, .robohash-001-yellow-face-08, .robohash-001-yellow-mouth-02,
.robohash-002-blue-accessory-07, .robohash-002-blue-body-03, .robohash-002-blue-eyes-10, .robohash-002-blue-face-08, .robohash-002-blue-mouth-04,
.robohash-002-brown-accessory-03, .robohash-002-brown-body-03, .robohash-002-brown-eyes-04, .robohash-002-brown-face-08, .robohash-002-brown-mouth-07,
.robohash-002-green-accessory-08, .robohash-002-green-body-02, .robohash-002-green-eyes-02, .robohash-002-green-face-03, .robohash-002-green-mouth-06,
.robohash-002-grey-accessory-07, .robohash-002-grey-body-04, .robohash-002-grey-eyes-04, .robohash-002-grey-face-01, .robohash-002-grey-mouth-01,
.robohash-002-orange-accessory-10, .robohash-002-orange-body-03, .robohash-002-orange-eyes-09, .robohash-002-orange-face-05, .robohash-002-orange-mouth-08,
.robohash-002-pink-accessory-01, .robohash-002-pink-body-05, .robohash-002-pink-eyes-02, .robohash-002-pink-face-03, .robohash-002-pink-mouth-08,
.robohash-002-purple-accessory-06, .robohash-002-purple-body-05, .robohash-002-purple-eyes-06, .robohash-002-purple-face-08, .robohash-002-purple-mouth-05,
.robohash-002-red-accessory-07, .robohash-002-red-body-08, .robohash-002-red-eyes-06, .robohash-002-red-face-02, .robohash-002-red-mouth-08,
.robohash-002-white-accessory-07, .robohash-002-white-body-06, .robohash-002-white-eyes-03, .robohash-002-white-face-06, .robohash-002-white-mouth-05,
.robohash-002-yellow-accessory-10, .robohash-002-yellow-body-09, .robohash-002-yellow-eyes-02, .robohash-002-yellow-face-05, .robohash-002-yellow-mouth-06,
.robohash-003-blue-accessory-03, .robohash-003-blue-body-07, .robohash-003-blue-eyes-02, .robohash-003-blue-face-01, .robohash-003-blue-mouth-05,
.robohash-003-brown-accessory-06, .robohash-003-brown-body-01, .robohash-003-brown-eyes-03, .robohash-003-brown-face-07, .robohash-003-brown-mouth-05,
.robohash-003-green-accessory-05, .robohash-003-green-body-06, .robohash-003-green-eyes-01, .robohash-003-green-face-06, .robohash-003-green-mouth-02,
.robohash-003-grey-accessory-09, .robohash-003-grey-body-01, .robohash-003-grey-eyes-08, .robohash-003-grey-face-08, .robohash-003-grey-mouth-07,
.robohash-003-orange-accessory-08, .robohash-003-orange-body-06, .robohash-003-orange-eyes-06, .robohash-003-orange-face-08, .robohash-003-orange-mouth-05,
.robohash-003-pink-accessory-06, .robohash-003-pink-body-08, .robohash-003-pink-eyes-06, .robohash-003-pink-face-10, .robohash-003-pink-mouth-01,
.robohash-003-purple-accessory-10, .robohash-003-purple-body-07, .robohash-003-purple-eyes-10, .robohash-003-purple-face-04, .robohash-003-purple-mouth-07,
.robohash-003-red-accessory-08, .robohash-003-red-body-05, .robohash-003-red-eyes-09, .robohash-003-red-face-05, .robohash-003-red-mouth-01,
.robohash-003-white-accessory-09, .robohash-003-white-body-04, .robohash-003-white-eyes-06, .robohash-003-white-face-08, .robohash-003-white-mouth-03,
.robohash-003-yellow-accessory-05, .robohash-003-yellow-body-07, .robohash-003-yellow-eyes-03, .robohash-003-yellow-face-04, .robohash-003-yellow-mouth-01,
.robohash-004-blue-accessory-05, .robohash-004-blue-body-04, .robohash-004-blue-eyes-03, .robohash-004-blue-face-05, .robohash-004-blue-mouth-01,
.robohash-004-brown-accessory-01, .robohash-004-brown-body-07, .robohash-004-brown-eyes-09, .robohash-004-brown-face-06, .robohash-004-brown-mouth-04,
.robohash-004-green-accessory-01, .robohash-004-green-body-04, .robohash-004-green-eyes-09, .robohash-004-green-face-07, .robohash-004-green-mouth-03,
.robohash-004-grey-accessory-05, .robohash-004-grey-body-10, .robohash-004-grey-eyes-03, .robohash-004-grey-face-06, .robohash-004-grey-mouth-02,
.robohash-004-orange-accessory-09, .robohash-004-orange-body-10, .robohash-004-orange-eyes-02, .robohash-004-orange-face-09, .robohash-004-orange-mouth-10,
.robohash-004-pink-accessory-10, .robohash-004-pink-body-09, .robohash-004-pink-eyes-10, .robohash-004-pink-face-01, .robohash-004-pink-mouth-07,
.robohash-004-purple-accessory-01, .robohash-004-purple-body-03, .robohash-004-purple-eyes-03, .robohash-004-purple-face-06, .robohash-004-purple-mouth-04,
.robohash-004-red-accessory-10, .robohash-004-red-body-10, .robohash-004-red-eyes-04, .robohash-004-red-face-03, .robohash-004-red-mouth-03,
.robohash-004-white-accessory-08, .robohash-004-white-body-07, .robohash-004-white-eyes-04, .robohash-004-white-face-10, .robohash-004-white-mouth-10,
.robohash-004-yellow-accessory-06, .robohash-004-yellow-body-02, .robohash-004-yellow-eyes-07, .robohash-004-yellow-face-10, .robohash-004-yellow-mouth-09,
.robohash-005-blue-accessory-09, .robohash-005-blue-body-05, .robohash-005-blue-eyes-05, .robohash-005-blue-face-10, .robohash-005-blue-mouth-02,
.robohash-005-brown-accessory-09, .robohash-005-brown-body-04, .robohash-005-brown-eyes-07, .robohash-005-brown-face-05, .robohash-005-brown-mouth-06,
.robohash-005-green-accessory-04, .robohash-005-green-body-07, .robohash-005-green-eyes-04, .robohash-005-green-face-08, .robohash-005-green-mouth-01,
.robohash-005-grey-accessory-10, .robohash-005-grey-body-05, .robohash-005-grey-eyes-10, .robohash-005-grey-face-04, .robohash-005-grey-mouth-09,
.robohash-005-orange-accessory-01, .robohash-005-orange-body-08, .robohash-005-orange-eyes-10, .robohash-005-orange-face-07, .robohash-005-orange-mouth-02,
.robohash-005-pink-accessory-08, .robohash-005-pink-body-06, .robohash-005-pink-eyes-04, .robohash-005-pink-face-04, .robohash-005-pink-mouth-04,
.robohash-005-purple-accessory-09, .robohash-005-purple-body-02, .robohash-005-purple-eyes-01, .robohash-005-purple-face-03, .robohash-005-purple-mouth-09,
.robohash-005-red-accessory-05, .robohash-005-red-body-04, .robohash-005-red-eyes-05, .robohash-005-red-face-10, .robohash-005-red-mouth-02,
.robohash-005-white-accessory-05, .robohash-005-white-body-02, .robohash-005-white-eyes-05, .robohash-005-white-face-09, .robohash-005-white-mouth-07,
.robohash-005-yellow-accessory-03, .robohash-005-yellow-body-10, .robohash-005-yellow-eyes-01, .robohash-005-yellow-face-06, .robohash-005-yellow-mouth-04,
.robohash-006-blue-accessory-04, .robohash-006-blue-body-01, .robohash-006-blue-eyes-06, .robohash-006-blue-face-02, .robohash-006-blue-mouth-06,
.robohash-006-brown-accessory-02, .robohash-006-brown-body-10, .robohash-006-brown-eyes-08, .robohash-006-brown-face-03, .robohash-006-brown-mouth-08,
.robohash-006-green-accessory-06, .robohash-006-green-body-03, .robohash-006-green-eyes-10, .robohash-006-green-face-04, .robohash-006-green-mouth-07,
.robohash-006-grey-accessory-06, .robohash-006-grey-body-06, .robohash-006-grey-eyes-07, .robohash-006-grey-face-07, .robohash-006-grey-mouth-04,
.robohash-006-orange-accessory-02, .robohash-006-orange-body-09, .robohash-006-orange-eyes-04, .robohash-006-orange-face-06, .robohash-006-orange-mouth-06,
.robohash-006-pink-accessory-03, .robohash-006-pink-body-07, .robohash-006-pink-eyes-09, .robohash-006-pink-face-06, .robohash-006-pink-mouth-05,
.robohash-006-purple-accessory-08, .robohash-006-purple-body-09, .robohash-006-purple-eyes-07, .robohash-006-purple-face-10, .robohash-006-purple-mouth-03,
.robohash-006-red-accessory-02, .robohash-006-red-body-07, .robohash-006-red-eyes-01, .robohash-006-red-face-04, .robohash-006-red-mouth-04,
.robohash-006-white-accessory-10, .robohash-006-white-body-05, .robohash-006-white-eyes-02, .robohash-006-white-face-05, .robohash-006-white-mouth-06,
.robohash-006-yellow-accessory-04, .robohash-006-yellow-body-05, .robohash-006-yellow-eyes-05, .robohash-006-yellow-face-01, .robohash-006-yellow-mouth-08,
.robohash-007-blue-accessory-10, .robohash-007-blue-body-06, .robohash-007-blue-eyes-01, .robohash-007-blue-face-09, .robohash-007-blue-mouth-08,
.robohash-007-brown-accessory-05, .robohash-007-brown-body-09, .robohash-007-brown-eyes-01, .robohash-007-brown-face-10, .robohash-007-brown-mouth-09,
.robohash-007-green-accessory-10, .robohash-007-green-body-10, .robohash-007-green-eyes-08, .robohash-007-green-face-02, .robohash-007-green-mouth-10,
.robohash-007-grey-accessory-02, .robohash-007-grey-body-07, .robohash-007-grey-eyes-09, .robohash-007-grey-face-05, .robohash-007-grey-mouth-05,
.robohash-007-orange-accessory-06, .robohash-007-orange-body-02, .robohash-007-orange-eyes-07, .robohash-007-orange-face-10, .robohash-007-orange-mouth-09,
.robohash-007-pink-accessory-09, .robohash-007-pink-body-10, .robohash-007-pink-eyes-07, .robohash-007-pink-face-05, .robohash-007-pink-mouth-06,
.robohash-007-purple-accessory-03, .robohash-007-purple-body-06, .robohash-007-purple-eyes-02, .robohash-007-purple-face-07, .robohash-007-purple-mouth-02,
.robohash-007-red-accessory-01, .robohash-007-red-body-06, .robohash-007-red-eyes-10, .robohash-007-red-face-01, .robohash-007-red-mouth-09,
.robohash-007-white-accessory-01, .robohash-007-white-body-09, .robohash-007-white-eyes-09, .robohash-007-white-face-04, .robohash-007-white-mouth-09,
.robohash-007-yellow-accessory-02, .robohash-007-yellow-body-03, .robohash-007-yellow-eyes-08, .robohash-007-yellow-face-09, .robohash-007-yellow-mouth-05,
.robohash-008-blue-accessory-06, .robohash-008-blue-body-08, .robohash-008-blue-eyes-08, .robohash-008-blue-face-04, .robohash-008-blue-mouth-09,
.robohash-008-brown-accessory-10, .robohash-008-brown-body-02, .robohash-008-brown-eyes-02, .robohash-008-brown-face-01, .robohash-008-brown-mouth-10,
.robohash-008-green-accessory-02, .robohash-008-green-body-05, .robohash-008-green-eyes-06, .robohash-008-green-face-01, .robohash-008-green-mouth-05,
.robohash-008-grey-accessory-08, .robohash-008-grey-body-08, .robohash-008-grey-eyes-01, .robohash-008-grey-face-09, .robohash-008-grey-mouth-06,
.robohash-008-orange-accessory-04, .robohash-008-orange-body-04, .robohash-008-orange-eyes-08, .robohash-008-orange-face-04, .robohash-008-orange-mouth-03,
.robohash-008-pink-accessory-05, .robohash-008-pink-body-02, .robohash-008-pink-eyes-08, .robohash-008-pink-face-09, .robohash-008-pink-mouth-10,
.robohash-008-purple-accessory-05, .robohash-008-purple-body-08, .robohash-008-purple-eyes-04, .robohash-008-purple-face-02, .robohash-008-purple-mouth-08,
.robohash-008-red-accessory-04, .robohash-008-red-body-02, .robohash-008-red-eyes-03, .robohash-008-red-face-07, .robohash-008-red-mouth-06,
.robohash-008-white-accessory-03, .robohash-008-white-body-03, .robohash-008-white-eyes-08, .robohash-008-white-face-03, .robohash-008-white-mouth-02,
.robohash-008-yellow-accessory-01, .robohash-008-yellow-body-08, .robohash-008-yellow-eyes-04, .robohash-008-yellow-face-03, .robohash-008-yellow-mouth-10,
.robohash-009-blue-accessory-08, .robohash-009-blue-body-02, .robohash-009-blue-eyes-04, .robohash-009-blue-face-06, .robohash-009-blue-mouth-03,
.robohash-009-brown-accessory-04, .robohash-009-brown-body-05, .robohash-009-brown-eyes-10, .robohash-009-brown-face-04, .robohash-009-brown-mouth-03,
.robohash-009-green-accessory-09, .robohash-009-green-body-09, .robohash-009-green-eyes-03, .robohash-009-green-face-05, .robohash-009-green-mouth-09,
.robohash-009-grey-accessory-04, .robohash-009-grey-body-02, .robohash-009-grey-eyes-02, .robohash-009-grey-face-02, .robohash-009-grey-mouth-10,
.robohash-009-orange-accessory-07, .robohash-009-orange-body-01, .robohash-009-orange-eyes-03, .robohash-009-orange-face-02, .robohash-009-orange-mouth-04,
.robohash-009-pink-accessory-04, .robohash-009-pink-body-04, .robohash-009-pink-eyes-03, .robohash-009-pink-face-08, .robohash-009-pink-mouth-09,
.robohash-009-purple-accessory-07, .robohash-009-purple-body-01, .robohash-009-purple-eyes-05, .robohash-009-purple-face-09, .robohash-009-purple-mouth-06,
.robohash-009-red-accessory-06, .robohash-009-red-body-03, .robohash-009-red-eyes-08, .robohash-009-red-face-09, .robohash-009-red-mouth-10,
.robohash-009-white-accessory-02, .robohash-009-white-body-10, .robohash-009-white-eyes-01, .robohash-009-white-face-02, .robohash-009-white-mouth-01,
.robohash-009-yellow-accessory-08, .robohash-009-yellow-body-01, .robohash-009-yellow-eyes-06, .robohash-009-yellow-face-07, .robohash-009-yellow-mouth-07
{ max-width: 100%; background-size: 100%; background-image: url('../assets/sprite.png'); }
</style>
