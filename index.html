<?php
    function getZodiacSign($birthdate){
        $signs = array(
            'Capricorn' => array('start' => '12-22', 'end' => '01-19'),
            'Aquarius' => array('start' => '01-20', 'end' => '02-18'),
            'Pisces' => array('start' => '02-19', 'end' => '03-20'),
            'Aries' => array('start' => '03-21', 'end' => '04-19'),
            'Taurus' => array('start' => '04-20', 'end' => '05-20'),
            'Gemini' => array('start' => '05-21', 'end' => '06-20'),
            'Cancer' => array('start' => '06-21', 'end' => '07-22'),
            'Leo' => array('start' => '07-23', 'end' => '08-22'),
            'Virgo' => array('start' => '08-23', 'end' => '09-22'),
            'Libra' => array('start' => '09-23', 'end' => '10-22'),
            'Scorpio' => array('start' => '10-23', 'end' => '11-21'),
            'Sagittarius' => array('start' => '11-22', 'end' => '12-21')
        );

        $month_day = date('m-d', strtotime($birthdate));
        $sign = '';

        foreach($signs as $key => $value){
            if (
                ($value['start'] <= $value['end'] && $month_day >= $value['start'] && $month_day <= $value['end']) ||
                ($value['start'] > $value['end'] && ($month_day >= $value['start'] || $month_day <= $value['end']))
            ) {
                $sign = $key;
                break;
            }
        }

        return $sign;
    }
?>

<style>
  body {
    background-image: url('https://assets.onecompiler.app/436vmj5t6/43mrhn7eu/Gradient%20numerology%20background%20_%20Free%20Vector.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    font-family: 'Segoe UI', sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}


    .container {
        background-color: #ffffff;
        border-radius: 15px;
        padding: 30px;
        box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        text-align: center;
        max-width: 400px;
        width: 100%;
    }

    h2 {
        color: #333;
        margin-bottom: 20px;
    }

    input[type="date"] {
        padding: 10px;
        font-size: 16px;
        width: 80%;
        border-radius: 8px;
        border: 1px solid #ccc;
    }

    .result {
        font-weight: bold;
        margin-top: 20px;
        background:rgb(143, 109, 153);
        color: #fff;
        font-size: 18px;
        padding: 10px;
        border-radius: 8px;
    }
</style>

<div class="container">
    <h2>Find Your Zodiac Sign</h2>
    <form id="zodiac-form" method="get">
        <input type="date" name="dob" onchange="submitForm();" value="<?php echo (isset($_GET['dob'])) ? $_GET['dob'] :''; ?>">
        <?php if (isset($_GET['dob'])) { ?>
            <div class="result">
                YOUR ZODIAC SIGN IS: <?php echo getZodiacSign($_GET['dob']); ?>
            </div>
        <?php } ?>
    </form>
</div>

<script>
    function submitForm() {
        document.getElementById('zodiac-form').submit();
    }
</script>
