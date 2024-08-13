<template>
 <div class="faq-list">
    <h1 class="faq-text-1">FAQ</h1>
    <faqItem
      v-for="(faq, index) in faqs"
      :key="index"
      :faq="faq"
    />
  </div>
</template>

<script>
    import faqItem from "./faqItem.vue";
    export default {
        components: {
            faqItem,
        },
        data() {
            return {
                faqs: [
                    {
                        question: 'What is a hackathon?',
                        answer: '...',
                    },
                    {
                        question: 'When is HackWashU?',
                        answer: 'bruh you don\'t even know when the hackathon is?',
                    },
                    {
                        question: 'who can attend?',
                        answer: 'idk... but not you',
                    },
                    {
                        question: 'What should I bring?',
                        answer: 'Your mom...',
                    },
                    {
                        question: 'is HackWashU in-person?',
                        answer: 'You think we\'d let you in person?',
                    },
                    {
                        question: 'is HackWashU free?',
                        answer: 'Pay up',
                    },
                    {
                        question: 'If I can\'t code, should I still come?',
                        answer: 'No',
                    },
                    {
                        question: 'Will there be swag?',
                        answer: 'You\'ll get a sticker',
                    },
                    {
                        question: 'i have more questions',
                        answer: 'too bad',
                    }
                ],
            };
        },
    };
</script>

<style scoped>
.faq-list{
    position: relative;
    height: auto;
    margin-bottom: 4vw;
    display: flex;
    width: 100vw;
    align-self: center;
    flex-direction: column;
}

.faq-text-1{
    width: 100vw;
    position: relative;
    text-align: center;
    font-family: 'FancyFont', serif;
    font-size: 6vw;
    display: flex;
    justify-content: center; 
    align-items: center; 
    margin-bottom: 2vw;
}

</style>
