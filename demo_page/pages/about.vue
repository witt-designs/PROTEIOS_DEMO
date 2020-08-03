<template>

    <div class="about">
        <div class="company">
            <h1>About Proteios.io</h1>
            <h2><a href="https://ipfs.io/">IPFS</a> - <a href="https://near.org/">NEAR Protocol</a></h2>

            <div class="red-border"></div>

            <p>Proteios.io is a project that brings together researchers and developers in blockchain, distributed systems, AI and genetics in order to create a web-based application with the goal of accelerating research and innovation in genetic engineering whether that be in drug discovery, vaccine development, disease biomarker identification, overall genome sequence analysis etc. Specifically, Proteios.io utilizes blockchain technology and the use of smart contracts to assist geneticists in the following two ways: 1) In order to create a marketplace where genetic research files/databases can be shared and exchanged securely for proper compensation 2) By creating an ecosystem where bioinformaticians utilizing machine learning can outsource the workload of labeling data to other individuals in exchange for compensation.</p>

            <img src="../assets/IPFS.png" class="ipfs_logo logos">
            <img src="../assets/near.png" class="ethereum_logo logos">
            
        </div>
    </div>


</template>

<script>


</script>


<style>

.company {
    color: white;
}

.company h1{

    font-family: sans-serif;
    margin-bottom: 40px;
    line-height: 80px;
    font-size: 65px;
    font-weight: 100;
    position: fixed;
    top: 17%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.company h2{

    font-family: sans-serif;

    margin: 14px 0;
    font-size: 25px;
    font-weight: 700;
    position: fixed;
    top: 85%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.company h2 a {
  &:hover {
    color: #03e9f4;
  }
}

.company p{

    font-family: sans-serif;
    text-align: center;
    margin-top: 40px; 
    margin-top: 20px;
    font-size: 24px;
    font-weight: 300;
    position: fixed;
    top: 44%;
    left: 50%;
    transform: translate(-50%, -50%); 
}

.red-border {
    width: 50%;
    border-bottom: 1px solid white;
    margin: 0 auto;
    height: 16px;
    position: fixed;
    top: 90%;
    left: 50%;
    transform: translate(-50%, -50%);
}



.ipfs_logo {
    position: absolute;
    top: 70%;
    width: 100px;
    left: 41%;

}

.ethereum_logo {
    position: absolute;
    top: 68%;
    width: 300px;
    left: 49%;
}

</style>
