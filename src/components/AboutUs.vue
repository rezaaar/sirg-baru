<template>
<div class="container-profile">
        <div class="team-container">
            <div class="text">MEET OUR TEAM</div>
        </div>
        <div class="row-profile">
            <div class="profile-card">
                <div class="profile-content">
                    <div class="profile-image">
                        <img src="@/assets/profile.jpg" alt="first user">
                    </div>
                    <div class="desc">
                        <h2>Wachid</h2>
                        <p>Backend</p>
                    </div>
                    <div class="profile-text">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
             <div class="profile-card">
                <div class="profile-content">
                    <div class="profile-image">
                        <img src="@/assets/profile.jpg" alt="first user">
                    </div>
                    <div class="desc">
                        <h2>Farida</h2>
                        <p>Frontend</p>
                    </div>
                    <div class="profile-text">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
             <div class="profile-card">
                <div class="profile-content">
                    <div class="profile-image">
                        <img src="@/assets/profile.jpg" alt="first user">
                    </div>
                    <div class="desc">
                        <h2>Valdo</h2>
                        <p>Backend</p>
                    </div>
                    <div class="profile-text">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
             <div class="profile-card">
                <div class="profile-content">
                    <div class="profile-image">
                        <img src="@/assets/profile.jpg" alt="first user">
                    </div>
                    <div class="desc">
                        <h2>Irfan</h2>
                        <p>Backend</p>
                    </div>
                    <div class="profile-text">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
             <div class="profile-card">
                <div class="profile-content">
                    <div class="profile-image">
                        <img src="@/assets/profile.jpg" alt="first user">
                    </div>
                    <div class="desc">
                        <h2>Reza</h2>
                        <p>Product Owner</p>
                    </div>
                    <div class="profile-text">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
             <div class="profile-card">
                <div class="profile-content">
                    <div class="profile-image">
                        <img src="@/assets/profile.jpg" alt="first user">
                    </div>
                    <div class="desc">
                        <h2>Tian</h2>
                        <p>Frontend</p>
                    </div>
                    <div class="profile-text">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AboutUs'
}
</script>

<style>
*{
    margin:0;
    padding:0;
}
.team-container
{
    width:100%;
    height: auto;
}

.text
{
    color:#14487A;
    font-size: 25px;
    margin-top: 40px;
    font-weight: 600;
    text-align: center;
 
}
.row-profile
{
    width: 60%;
    margin:auto;
    margin-bottom: 40px;
    margin-top: 20px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-items: center;
    justify-content: center;
}
@media(max-width: 768px)
{
    .row-profile{
        width: 100%;
    }
}
.profile-card
{
    width: 270px;
    height: 250px;
    margin: 20px 10px 10px 10px;
}
@media(max-width: 468px)
{
    .profile-card
    {
        width: 290px;
        height: 250px;
    }
}
.profile-content
{
    padding:15px;
}
.profile-image img{
    width: 80px;
    height: 80px;
    border-radius: 50px;
}
.profile-image
{
    text-align: center;
}
.desc
{
    text-align: center;
}
.desc h2
{
    color: #14487A;
    font-weight: bold;
    font-size: 20px;
}
.desc p{
    font-size: 13px;
    font-weight: bold;
    color: #000000;
     
}

.profile-text p{
    text-align: center;
}
</style>