<template>
      <section id="contact">
        <div class="container shadow p-3 mb-5 bg-body rounded">
            <h1>Contact me</h1>
            <div class="row " id="about-area">
              <div class="col-md-4">
                <iframe id="animation" src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d52847.932331868935!2d18.864726!3d-34.120858!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1dcdca5228bfab99%3A0xfa579031c0ea9162!2s19173%20Nonqubela%20St%2C%20Lwandle%2C%20Cape%20Town%2C%207143%2C%20South%20Africa!5e0!3m2!1sen!2sus!4v1652359541452!5m2!1sen!2sus"  allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="rounded"></iframe>
              </div>
              <div class="col-md-8">
                <form action="https://formspree.io/f/meqnvgjj"
                method="POST">
                  <div class="row">
                    <div class="col-md-6 mt-3">
                    <input type="name" class="form-control shadow-sm p-3 mb-5 bg-body rounded" id="name" placeholder="Name" name="name"></div>
                    <div class="col-md-6 mt-3">
                    <input type="email" class="form-control shadow-sm p-3 mb-5 bg-body rounded" id="email" placeholder="Email" name="email"></div>
                    <div class="mt-3 ">
                    <input type="phone" class="form-control shadow-sm p-3 mb-5 bg-body rounded" id="phone" placeholder="Phone number" name="phone"></div>
                </div>
                <div class="row">
                    <div class=" mt-3 ">
                    <textarea type="text" class="form-control textarea shadow-sm p-3 mb-5 bg-body rounded" id="text" placeholder="Message" name="message"></textarea></div>
                <div class="row display-flex justify-content-evenly">
                    <div class="col-auto mt-3 mb-3">
                        <button type="submit" class="btn" id="submit">Send Message</button>
                      </div>
                </div>
                </div>
                </form>
              </div>
            </div>
        </div>
    </section>  
</template>

<script>
export default {
    return(){
    imgURL:'https://i.postimg.cc/6pPBpjVw/Siyolise-1.jpg'
    }
}
</script>

<style scoped>

    .col-md-4{
      display: flex;
      justify-content: center;
    }
    .col-md-8{
      display: flex;
      justify-content: center;
    }
    .btn{
      margin-top: 20px;
      padding: 5px;
      border-radius: 15px;
      background-color: #8A77A0;
    }
    .form-control{
      /* border: none; */
      border: nonw;
    }
    section{
    background-color: #EBE2F4;
    height:100vh;
  }
</style>