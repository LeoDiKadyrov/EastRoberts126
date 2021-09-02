<template>
    <div class="main-div h-screen text-center flex justify-around items-center">
        <div class="w-max">
            <p class="main__subheader text-white font-medium font-sans w-5/12 mb-2 text-2xl">
            Welcome to Danny's house!
            I am landlord from Wildwood. I have been doing this for more than 10 years.
            </p>
            <div class="main__text">
                <p class="text-white font-medium w-5/12 text-xs mb-2">Rent is $100 a week for each bed.
                There is a $200 deposit to be given at time of rental.</p>
                <p class="text-white font-medium w-5/12 text-xs mb-2">Comforts: Wi-Fi, comfortable common living area, dining room, complete kitchen and bathroom</p>
                <p class="text-white font-medium w-5/12 text-xs">East Roberts Ave 126. - Wildwood, New Jersey, 08260</p>
            </div>
        </div>
        <div class="main__form text-white flex w-1/5 justify-center rounded">
            <form action="https://getform.io/f/99a5dd2b-8888-4232-a0f7-bf52a2b95931" method="POST">
                <div class="form__contacts">
                    <h3>Contact me</h3>
                    <p>Mobile: +1 609 425 7758 (Whatsapp)</p>
                    <p>Email: jppolini101@gmail.com</p>
                </div>
                <div class="text-black flex flex-col m-2 form__text">
                    <input type="text" placeholder="Your Name" class="mb-2" name="name">
                    <input type="email" placeholder="Your E-mail" class="mb-2" name="email">
                    <input type="text" placeholder="Phone Number" class="mb-2" name="phone">
                    <div class="form__genders">
                        <input type="radio" name="gender" id="gender-male" value="male"> 
                        <label for="gender-male" class="mx-2">Male</label>
                        <input type="radio" name="gender" id="gender-female" value="female"> 
                        <label for="gender-female" class="mx-2">Female</label>
                    </div>
                    <div class="form__dates my-2 flex flex-col">
                        <label for="date-arrival">Arrival date: </label>
                        <input type="date" id="date-arrival" name="arrival date">
                        <label for="date-departure">Departure date: </label>
                        <input type="date" id="date-departure" name="departure date">
                    </div>
                    <input type="text" name="number of people" id="num-people" placeholder="How many people are coming?">
                    <textarea name="info" id="1" cols="30" rows="10" class="my-2" placeholder="When contacting me please include information such as:
- Single or couple
- If you are a group, How many in your group and gender of each
- How did you find us"></textarea>
                    <button class="bg-white form__submit">Send Message</button>
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
    background: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ), url("../assets/street_view.jpg") center no-repeat;
    background-size: cover;
}
.main__subheader {
    font-family: "Source Sans Pro";
}
.main__text {
    font-family: "Open Sans";
}
.main__form {
    background: linear-gradient( rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5) ); 
}
.form__contacts {
    color: #987654;
}
.form__text {
    color: #afaeae;
}
.form__submit {
    font-family: "Roboto";
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