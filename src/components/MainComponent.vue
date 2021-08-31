<template>
    <div class="main-div h-screen text-center flex justify-around items-center">
        <div class="w-max">
            <p class="text-white font-medium font-sans w-5/12 mb-2 text-2xl">
            Welcome to Danny's house!
            I am landlord from Wildwood. I have been doing this for more than 10 years.
            </p>
            <p class="text-white font-medium font-sans w-5/12 text-xs mb-2">Rent is $100 a week for each bed.
            There is a $200 deposit to be given at time of rental.</p>
            <p class="text-white font-medium font-sans w-5/12 text-xs mb-2">Comforts: Wi-Fi, comfortable common living area, dining room, complete kitchen and bathroom</p>
            <p class="text-white font-medium font-sans w-5/12 text-xs">East Roberts Ave 126. - Wildwood, New Jersey, 08260</p>
        </div>
        <div class="bg-black text-white flex">
            <form>
                <div>
                    <h3>Contact me</h3>
                    <p>Mobile: +1 609 425 7758</p>
                    <p>Email: jppolini101@gmail.com</p>
                </div>
                <div class="text-black flex">
                    <input type="text" placeholder="Your Name">
                    <input type="email" placeholder="Your E-mail">
                    <input type="text" placeholder="Phone Number">
                    <textarea name="info" id="1" cols="30" rows="10"></textarea>
                    <button class="bg-white">Send Message</button>
                </div>
            </form>
        </div>
    </div>
</template>

<script>
export default {
    name: "MainComponent"
}
</script>

<style scoped>
.main-div {
    background: url("../assets/street_view.jpg") center no-repeat;
    background-size: cover;
}
</style>

/* Accommodation price:

Comforts: Wi-Fi, comfortable common living area, dining room, complete kitchen and bathroom.

From JFK International Airport: Take the NYC Airporter to the Port Authority Bus Terminal. After you get to the Port Authority, Take the New Jersey Transit Bus 319 OR Greyhound Bus to Atlantic City.When you arrive at the Atlantic City Bus Terminal take Bus 552 to the Wildwood Bus Terminal.
From Philadelphia International Airport: Take the SEPTA Airport Regional Rail Line to the 30th Street Station. Take Train 4639 to Atlantic City. Take the New Jersey Transit Bus 552 to Wildwood bus terminal
From Wildwood Bus Terminal: A 5 minute walk.Turn left onto New Jersey Ave, Turn right onto Roberts Ave then the house will be on the right.

Note:When contacting me please include information such as:

Date and length of your stay
Are male or female
Single or couple
If you are a group, How many in your group and gender of each
How did you find us */