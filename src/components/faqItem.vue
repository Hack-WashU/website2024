<template>
    <div class="faq-item">
      <button @click="toggle" class="faq-question">
        {{ faq.question }}
        <span>{{ isOpen ? '-' : '+' }}</span>
      </button>
      <div v-if="isOpen" class="faq-answer">
        {{ faq.answer }}
      </div>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      faq: Object,
    },
    data() {
      return {
        isOpen: false,
      };
    },
    methods: {
      toggle() {
        this.isOpen = !this.isOpen;
      },
    },
  };
  </script>
  
  <style scoped>
  .faq-item {
    /* margin-bottom: 0.3vw; */
    margin-left:30vw;
    display: flex;
    justify-content: left;
    align-items: center;
    position: relative;
    width: 32vw;
    flex-direction: column;
    font-family: 'spartan-sb', serif;
  }
  
  .faq-question {
    background-color: transparent;
    border: none;
    padding: 10px;
    text-align: left;
    color: #ffffff;
    font-size: 1.8vw;
    width: 100%;
    cursor: pointer;
  }
  
  .faq-answer {
    padding: 10px;
    background-color: transparent;
    border-left: 3px solid #dbdbdb;
    text-align: left;
    width: 100%;
    display: flex;
  }
  </style>
  