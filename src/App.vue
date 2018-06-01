<template>
    <div>
        <image-Carousel :images="images" :params="{minMoveDistance: 50, autoPlay: true}"></image-Carousel>


    </div>
</template>

<script>
import ImageCarousel from "./components/ImageCarousel.vue";
export default {
  name: "app",
  components: {
    [ImageCarousel.name]: ImageCarousel
  },
  data() {
    return {
      images: [
        {
            "clickUrl": "https://codepen.io/koucxz/pen/vxVGMG",
            "desc": "slide1",
            "image": "http://img.fzg.maplegz.com/4dd3cbff-e6f8-4f84-86f9-868d691eaf5e.webp"
        },
        {
            "clickUrl": "#",
            "desc": "slide2",
            "image": "http://img.fzg.maplegz.com/a2a2b90e-9f03-4271-99b0-c1e3900ac263.webp"
        },
        {
            "clickUrl": "#",
            "desc": "slide3",
            "image":  "http://img.fzg.maplegz.com/4c3b1d7f-a256-4564-af7c-bfee4a3af120.webp"
        },     
        {
            "clickUrl": "#",
            "desc": "slide4",
            "image": "http://img.fzg.maplegz.com/c40961e5-5a61-450f-9d91-89778586ddad.webp",
        },
        {
            "clickUrl": "https://www.csdn.net/",
            "desc": "slide5",
            "image":  "http://img.fzg.maplegz.com/e7822af1-87d0-422b-b7fe-407d0f45a4c2.webp"
        }
      ]
    };
  },
  methods: {}
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
