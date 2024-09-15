<template>
 
 <ArticleComponent/>
 

 <article>
        <h4>Toto bude clanok o HTML</h4>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum ab doloribus, nemo, ipsum, perferendis vel
            blanditiis cum iure doloremque nihil corporis quas illum quidem rerum sequi recusandae. Possimus,
            reiciendis. Fugiat?
        </p>

        
            <h5>Navod</h5>
            <ol>
                <li>stiahnut vs code</li>
                <li>nainstalovat extensions</li>
                <li>nieco</li>
            </ol>

        <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione temporibus unde vitae neque, sunt assumenda reiciendis quae optio, velit, sit dolores voluptas perferendis aliquid? Dolores veritatis praesentium enim omnis quis?
            Quos fugiat enim repellendus fugit. Earum dolorem ipsa provident, est iure pariatur dolores molestias unde? Quia vitae voluptatibus molestias. Pariatur, eaque ducimus praesentium aspernatur est labore provident eum totam nihil.
            Asperiores, deseradasdaunt? Nihil molestias minima autem labore distinctio et maxime cumque, rem expedita, illum excepturi consequatur! Delectus, optio! Eum quasi distinctio voluptas non neque cum laborum sint corrupti dolorem quos.
            Quasi distinctio modi totam praesentium, iusto voluptas deleniti facere natus, quod aut blanditiis accusantium pariatur nisi hic vitae mollitia voluptates quibusdam repudiandae? Sunt vel eos pariatur ipsam eum nulla natus.
            Quis quod quidem voluptates necessitatibus in suscipit fugiat neque ipsam a earum beatae officiis, eos nulla assumenda, quae aperiam sit excepturi autem, perferendis explicabo placeat est expedita reiciendis eius. Dolores.
        </p>

        <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Officiis beatae, est inventore magnam recusandae odit deserunt, aliquam illum sapiente iusto nemo vel asperiores error ex, quo enim! Neque, hic incidunt?
            Excepturi provident enim quam amet facilis, itaque, beatae distinctio, labore iste similique reiciendis. Quasi vero accusamus quae placeat. Sunt veritatis illum similique iste totam! Eius temporibus eligendi molestias nisi nam?
        </p>
        <img class="article-image" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ4tZWVFCDi-UBtRvugXE-AcaDj-dx6QPRChw&s" alt="cute dog">
    </article>


    <article>
        <h4>Toto bude o CSS</h4>

        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam consectetur in eos quis aperiam exercitationem similique nam, minima odio enim laboriosam libero mollitia, non est, debitis repudiandae pariatur. Laboriosam, cum?
            Ad quas, in dicta vero molestiae natus unde provident deserunt delectus consequatur, ipsam ut ducimus nemo iste minus aliquid quis corporis neque illo facere, repellendus nesciunt? Voluptatum minima quo deleniti.
        </p>

        
            <h5>Poziadavky</h5>

            <ul>
                <li>Trpzelivost</li>
                <li>Trpzelivost</li>
                <li>design citenie</li>
                <li><a target="_blank" href="https://www.youtube.com/watch?v=LULd0858mUQ">Este nieco super paradne</a></li>
            </ul>
        

        <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus culpa, libero eum sequi dignissimos ipsam cum praesentium quibusdam modi corrupti, veritatis blanditiis. Inventore non omnis fugiat ipsam amet molestiae modi!
        </p>



        <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Maiores minima similique, impedit quaerat tempora rerum porro vero? Nobis iste quaerat, ipsam facilis totam magni eius, vero aliquam quas molestias dolor.
            Distinctio magnam quos quaerat molestias officia nisi, provident illum, porro doloribus ab cum placeat. Ipsam totam voluptas ipsa impedit voluptatibus magnam, quod quia dignissimos, laudantium nobis aliquam, inventore voluptates perspiciatis.
            Pariatur maiores, autem neque tempore officiis, dolorem molestiae quidem natus expedita, iure culpa aut aspernatur voluptate eum ipsa atque unde? Ratione eligendi nam, inventore aliquid ad nulla qui! Error, quae.
        </p>
        <img class="article-image" src="https://images.prismic.io/turing/652ebea8fbd9a45bcec8188d_What_Goes_Behind_Writing_a_Flawless_CSS_Code_37742e2bcf.webp?auto=format,compress" alt="cute dog">
    </article>

</template>

<script>

import ArticleComponent from './ArticleComponent.vue';


export default {
  name: 'App',
  components: {
    ArticleComponent,
    
  }
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h4 {
    color: darkred;
}

article {
    border: 2px solid darkviolet;
    border-radius: 15px;
    margin: 20px;
    padding: 10px;
}

.non-article-heading {
    color: blue;
}

.footer-image {
    width: 20%;
}

.article-image {
    width: 20ex;
    display: block;
    margin-left: auto;
    margin-right: auto;
    border-radius: 50px;
}

footer {
text-align: center;
background-color: aliceblue;
padding: 10px;
}

header {
    padding: 10px;
    text-align: center;
    background-color: aliceblue;
}

body {
    margin: 0;
}

a {
    color: rgb(57, 57, 57);
}
nav {
    list-style-type: none;
    padding: 0;
    margin: 0;
    display: inline-block;
    margin-right: 15px;
    height: 2em;
}


nav a {
    font-size: 16px;
    text-decoration: none;
    transition: font-size 0.3s ease;
}

nav a:hover {
    font-size: 20px;
    color: darkmagenta;
}


.contact-form {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
    margin-left: auto;
    margin-right: auto;
}
.contact-form h2 {
    margin-bottom: 20px;
    font-size: 24px;
    text-align: center;
}
.contact-form input[type="text"],
.contact-form input[type="email"],
.contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
    font-size: 16px;
}
.contact-form textarea {
    height: 150px;
    resize: vertical;
}
.contact-form button {
    width: 100%;
    padding: 10px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    font-size: 18px;
    cursor: pointer;
}
.contact-form button:hover {
    background-color: #45a049;
}
</style>
