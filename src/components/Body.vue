<template>
    <div class="hello">
        <div class="row">
            <div class="column">
                    <img class='staticimg' src='https://i.ibb.co/F6Vj7XK/endless1.jpg' />
                    <img class='staticimg' src='https://i.ibb.co/j4n36T7/endless2.jpg' />
            </div>

            <div class="column">
                    <img class='staticimg' src='https://i.ibb.co/dc7rYHq/endless5.jpg' />
                    <img class='staticimg' src='https://i.ibb.co/CW9Yn9B/endless6.jpg' />
            </div>

            <div class="column">
                    <img class='staticimg' src='https://i.ibb.co/dJkXtML/endless7.jpg' />
                    <img class='staticimg' src='https://i.ibb.co/DzTBJdh/endless8.jpg' />
            </div>
        </div>
  </div>
</template>

<style>

@media (min-width: 600px) {

    .hello {
        align-items: center !important;
        justify-content: center !important;
    }

    .row {
            align-items: center !important;
            justify-content: center !important;
            display: -ms-flexbox; /* IE10 */
            display: flex;
            -ms-flex-wrap: wrap; /* IE10 */
            flex-wrap: wrap;
            padding: 0 4px;
    }

    .column {
        -ms-flex: 25%; /* IE10 */
        flex: 25%;
        max-width: 25%;
        padding: 0 4px;
    }

    .staticimg{
        padding-top: 10px;
        width: 100%;
    }
    .card-deck {
        display: flexbox;
    }

    .card {
        border-radius: 10px;
    }

    .card-text {
        font-family: Arial;
        font-size: 18px;
    }
    .sm-img {
        background-repeat: no-repeat;
        border-radius: 10px;
    }

    .btn-container {
        display: flex;
        justify-content: center;
        align-items: center;
        padding-bottom: 20px;
    }

    .btn-readmore {
        border-radius: 30px;
        border-width: 3px;
        border-color: #000;
        height: 40px;
        width: 200px;
        text-transform: uppercase;
        font-family: Arial;
        font-weight: 600;
        padding-bottom: 20px;
        padding-top: 8px;
    }
}


</style>

