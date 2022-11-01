<div class="solution">
    <div class="discover">
        <div class="sol-title">
            <h2>Discover</h2>
            <img src="./discover.png" alt="An orange wearing green headphones">
        </div>
        <div class="sol-desc">
            <p>
                Discover music like a human.  
            </p>
        </div>
    </div>
    <div class="interact">
        <div class="sol-title">
            <h2>Interact</h2>
            <img src="./interact.png" alt="An orange and a lime wearing headphones and shaking hands">
        </div>
        <div class="sol-desc">
            <p>
                Build direct relationships. 
            </p>
        </div>
    </div>
    <div class="grow">
        <div class="sol-title">
            <h2>Grow</h2>
            <img src="./grow.png" alt="An orange in a rocketship">
        </div>
        <div class="sol-desc">
            <p>
                Grow with your tribe. 
            </p>
        </div>
    </div>
</div>

<style>
@media (max-width: 800px) {
    .discover {
        flex-direction: column;
    }
    .interact {
        flex-direction: column;
    }
    .grow {
        flex-direction: column;
    }
}
p {
    margin-right: 25px;
    font-weight: bold;
    margin-left: 50px;
}
img {
    max-width: 75%;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
h2 {
    color: #ffac33;
}
.solution {

background-color: white;
min-height: 300px;

color: black;

}
.discover {
/* min-width: 33.33%;
min-height: 200px; */
display: flex; 
align-items: center;
padding: 20px;
/* padding-left: 30px; */
border-top: 3px solid #3ed957;
}
.sol-title {
    display: flex;
    flex-direction: column;
    text-align: center;
    max-width: 50%;
}
.sol-desc {
    max-width: 70%;
    text-align: left;
    align-content: center;
}

.interact {
/* min-width: 33.33%;
min-height: 200px; */
display: flex;
align-items: center;
border-top: 3px solid #ffac33;
}
.grow { 
/* min-width: 33.33%;
min-height: 200px; */
display: flex;
align-items: center;
border-top: 3px solid #ffac33;
padding: 20px;
}

</style>