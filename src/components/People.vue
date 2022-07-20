<template>
    <div id="testimonials">
        <div v-for="testimonial in testimonials" :key="testimonial.id">
            <img :src="testimonial.imgurl">
            <div class="info">
                <h1>{{testimonial.name}}</h1>
                <p>{{testimonial.comment}}</p>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    data(){
        return{
            "testimonials":[
                {
                    "id":"1",
                    "imgurl":"https://i.postimg.cc/sDP7NKLf/jason.jpg",
                    "name":"Jason Wandrag",
                    "comment":"Siyolise is a hardworking and dedicated young lady, who has been constantly striving to improve herself. Over the short time that I have known her, she has improved immensely and has overcome every challenge thrown at her. I wish her the best in her future ventures."
                },
                {
                    "id":"2",
                    "imgurl":"https://i.postimg.cc/Njdcpq76/smangele.jpg",
                    "name":"Smangele Mntungwa",
                    "comment":"Siyolise is a kind-hearted, trustworthy and compassionate person. She has unlimited potential. I believe that she is strong and unshaken, and will complete anything she set her sights on."
                },
                {
                    "id":"3",              
                    "imgurl":"https://i.postimg.cc/tg9jzRxC/Sabelo.jpg",
                    "name":"Sabelo Mdashe",
                    "comment":"Siyolise has the ability to befriend anyone she meets, as she is a natural extrovert and is noticeably confident. She interacts well with everyone because of her confidence and her amicable and very sincere personality. Aside from enjoying a wide circle of loyal friends and peers, Siyolise also has the respect of her colleagues."
                },
                {
                    "id":"4",              
                    "imgurl":"https://i.postimg.cc/W1v3Qvkx/sibonile.jpg",
                    "name":"Sibonile Nyalambisa",
                    "comment":"Siyolise is polite and respectful. She is a great communicator and can manage people to get tasks done on time."
                },
                {
                    "id":"5",                   
                    "imgurl":"https://i.postimg.cc/m23pyYNC/Lihle.jpg",
                    "name":"Lihle Goliath",
                    "comment":"Siyolise is a kind-hearted, trustworthy and compassionate person. She has unlimited potential. I believe that she is strong and unshaken, and will complete anything she set her sights on."
                }
            ]
        }
    }
}
</script>
<style>
    
</style>