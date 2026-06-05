# Hosting-Plans-Section-with-Pricing-Cards.
<section class="plans-section">
   <div class="plans-heading">
        <h2>Choose Your Hosting Plan</h2>
        <p>
            Fast, secure and affordable hosting solutions for every website.
        </p>
    </div>
    <div class="plans-container">
          <div class="plan-card">
            <h3>Standard</h3>
            <h1>₹549/year</h1>
            <ul>
                <li>✔ 1 Website</li>
                <li>✔ 2 GB SSD Storage</li>
                <li>✔ 50 GB Bandwidth</li>
                <li>✔ Free SSL</li>
            </ul>
            <button>Buy Now</button>
        </div>
        <div class="plan-card">
            <h3>Advance</h3>
            <h1>₹849/year</h1>
            <ul>
                <li>✔ 5 Websites</li>
                <li>✔ 5 GB SSD Storage</li>
                <li>✔ 100 GB Bandwidth</li>
                <li>✔ Free SSL</li>
            </ul>
            <button>Buy Now</button>
        </div>
        <div class="plan-card">
            <h3>Unlimited</h3>
            <h1>₹1099/year</h1>
            <ul>
                <li>✔ 10 Websites</li>
                <li>✔ Unlimited SSD Storage</li>
                <li>✔ Unlimited Bandwidth</li>
                <li>✔ Free SSL</li>
            </ul>
            <button>Buy Now</button>
        </div>
        .plans-section{
    padding:80px 5%;
    background:#f5f5f5;
}
      
</> CSS

.plans-heading{
    text-align:center;
    margin-bottom:50px;
}

.plans-heading h2{
    font-size:42px;
    color:#2b1467;
}

.plans-heading p{
    color:#666;
}

.plans-container{
    display:flex;
    justify-content:center;
    gap:25px;
    flex-wrap:wrap;
}

.plan-card{
    width:300px;
    background:white;
    padding:30px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.plan-card h3{
    color:#2b1467;
}

.plan-card h1{
    margin:20px 0;
}

.plan-card ul{
    list-style:none;
    margin-bottom:20px;
}

.plan-card ul li{
    margin:10px 0;
}

.plan-card button{
    width:100%;
    padding:12px;
    border:none;
    background:#0f52d6;
    color:white;
    border-radius:5px;
    cursor:pointer;
}
    </div>
</section>
