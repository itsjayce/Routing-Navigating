<template>
    <div class="blog">
        <h1>{{ title }}</h1>
        <div class="container">
            <div class="intro">
                <p>Hi coffee lovers! Have you ever wondered how that simple brown bean transforms into a diverse range of flavors? The answer lies in the roast! As this play a significant role in unlocking the unique characteristics of each coffee bean. The roasting spectrum can be categorized into four main types.</p>
            </div>
            <div class="img">
                <h4>Light Roast</h4>
                <img src="./assets/2.jpg" alt="" width="70%">
                <p>The beans are roasted quickly at a low temperature. which retains the bean’s natural characteristics. They are known for their bright acidity, subtle sweetness and the delicate flavors that often reflect the origin of the beans. This roast tend to have slightly more caffeine due to denser beans. However, the brewing process can also affect the caffeine content.</p>
            </div>
            <div class="img">
                <h4>Medium Roast</h4>
                <img src="./assets/3.jpeg" alt="" width="70%">
                <p>This is also known as the “perfect spot” for coffee drinkers. This roast offers a balanced acidity and body, with a more pronounced sweetness and richer flavor compared to light roasts.</p>
            </div>
            <div class="img">
                <h4>Medium-Dark Roast</h4>
                <img src="./assets/4.jpeg" alt="" width="70%">
                <p>As the roast elevates, the acidity settles further, as the coffee becomes more flavorsome. The bitterness in the coffee bean starts to develop, and caramel notes become more prominent.</p>
            </div>
            <div class="img">
                <h4>Dark Roast</h4>
                <img src="./assets/5.jpeg" alt="" width="70%">
                <p>AThe beans are roasted for the longest duration with the highest temperatures. The beans have a bold, smoky flavor with minimal acidity. The bean’s characteristics are almost gone, and the intense roast notes dominates the cup.</p>
            </div>
        </div>

        
    </div>
</template>

<script>
export default {
    name: 'blog',
    data(){
        return{
            title:'Blog: All About Beans'
        }
    }
}
</script>

<style scoped>
.blog {
    display: flex;
    flex-direction: column;
    justify-content: center;
}
p {
    align-items: center;
    padding:1em;
    justify-content: center;

}
</style>