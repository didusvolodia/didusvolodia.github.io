<!DOCTYPE html>
<html lang="en">
<head>
    <title>Сад чудес - "Виграйте саджанець ТРОЯНДИ, ЧУДО-ВИШНІ, МАЛИНИ"</title>
    <!--<meta name="viewport" content="width=device-width, user-scalable=yes">-->
    <meta name="viewport" content="user-scalable=no">
    <meta name="viewport" content="width=500">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <link rel="stylesheet" media="all" href="/application/views/promo/igra-sad-chudes/css/fonts/fonts.css"/> <!--/application/views/promo/lucky-three-game/-->
    <link rel="stylesheet" media="all" href="/application/views/promo/igra-sad-chudes/css/styles.css?v=7"/>
    <!-- Google Tag Manager -->
    <script>(function (w, d, s, l, i) {
            w[l] = w[l] || [];
            w[l].push({
                'gtm.start':
                    new Date().getTime(), event: 'gtm.js'
            });
            var f = d.getElementsByTagName(s)[0],
                j = d.createElement(s), dl = l != 'dataLayer' ? '&l=' + l : '';
            j.async = true;
            j.src =
                'https://www.googletagmanager.com/gtm.js?id=' + i + dl;
            f.parentNode.insertBefore(j, f);
        })(window, document, 'script', 'dataLayer', 'GTM-PRSNDK');</script>
    <!-- End Google Tag Manager -->
</head>
<body>
<!-- Google Tag Manager (noscript) -->
<noscript>
    <iframe src="https://www.googletagmanager.com/ns.html?id=GTM-PRSNDK"
            height="0" width="0" style="display:none;visibility:hidden"></iframe>
</noscript>
<!-- End Google Tag Manager (noscript) -->
<style>
    .bezp {
        margin-bottom: 20px;
    }
</style>
<?php

if (isset($_GET['clearallfiles'])) {
    unlink('all_promos');
    unlink('promowins');
    die('ok');
}

function getUserHostAddress()
{
    if (!empty($_SERVER['HTTP_X_REAL_IP']))   //check ip from share internet
    {
        $ip = $_SERVER['HTTP_X_REAL_IP'];
    } elseif (!empty($_SERVER['HTTP_CLIENT_IP']))   //check ip from share internet
    {
        $ip = $_SERVER['HTTP_CLIENT_IP'];
    } elseif (!empty($_SERVER['HTTP_X_FORWARDED_FOR']))   //to check ip is pass from proxy
    {
        $ip = $_SERVER['HTTP_X_FORWARDED_FOR'];
    } else {
        $ip = $_SERVER['REMOTE_ADDR'];
    }
    return $ip;
}


$promopath = 'ua';
$all_promos = array();
$time1 = time();

$activenumbers = array(
    'malina' => 2,
    'roza' => 0,
    'vishnya' => 4,
);

$ip = getUserHostAddress();

$ipkey = ip2long($ip);
if (file_exists('promowins'))
    $promowins_str = file_get_contents('promowins');
else
    file_put_contents('promowins', serialize(array()));

$promowins = array();
if (!empty($promowins_str))
    $promowins = unserialize($promowins_str);


if (!empty($promowins[$ipkey])) {
    $promocode = $promowins[$ipkey]['promocode'];
    $winarray = $promowins[$ipkey]['winarray'];
}

//var_dump($promocode,$winarray); die();
if (empty($promocode)) {
    if (!file_exists('all_promos')) {
        foreach (array('malina', 'roza', 'vishnya') as $v) {
            $csv = file_get_contents('application/views/promo/igra-sad-chudes/promocodes/' . $promopath . '/' . $v . '/export_promo_code.csv'); //application/views/promo/lucky-three-game/
            $csv = explode("\n", $csv);

            if (!empty($csv))
                foreach ($csv as $cv) {
                    if (!empty($cv))
                        $all_promos[$v][] = $cv;
                }
        }
        file_put_contents('all_promos', serialize($all_promos));
    } else $all_promos = unserialize(file_get_contents('all_promos'));

    $c = 0;
    foreach ($all_promos as $k => $v) {
        if (empty($v))
            unset($all_promos[$k]);
    }

    $ks = array_keys($all_promos);
    $win = $ks[mt_rand(0, count($ks) - 1)]; // Выбрали малина или хуиня

    $aw = $activenumbers[$win];
    $winarray = $aw;

    $winkey = mt_rand(0, count($all_promos[$win]) - 1);
    if (empty($all_promos[$win][$winkey])) {
        header('HTTP/1.1 500 Internal Server Error');
        die();
    }
    $promocode = $all_promos[$win][$winkey];
    unset($all_promos[$win][$winkey]);
    $all_promos[$win] = array_values($all_promos[$win]);
    file_put_contents('all_promos', serialize($all_promos));

    $promowins[$ipkey]['promocode'] = $promocode;
    $promowins[$ipkey]['winarray'] = $winarray;
    file_put_contents('promowins', serialize($promowins));

} else { ?>
    <script>
        var rlotwind = '<?=$promocode?>';
    </script>
<?php }

?>
<div class="luchi" style="display: none"></div>

<div class="container">
    <div class="frukti" style="display: none"></div>
    <div class="logo1 ua"></div>
    <div class="top_zvezda"></div>
    <div class="otdo ua"></div>
    <div id="not_played" style="display: none">


        <div class="heading ua"></div>

        <div class="roulette_container">
            <div class="nadroulette"></div>
            <div class="podrul"></div>
            <div class="roulette" style="    transform: rotate(28deg);"></div>
            <div class="price"></div>

        </div>
        <div class="rule_niz"></div>
        <div class="play">
            <button class="btn btn-large btn-primary start" data-roulette="0"><span>Крутити барабан!</span></button>

        </div>
        <div class="ps">Крутiть барабан <br/><span>i забирайте приз!</span></div>
        <div class="rules">
            <div class="rtitle">Правила гри Сад чудес:
            </div>
            <div class="rule">
                <div class="star">1</div>
                <div class="stext">
                    <div class="vstext">Ви один раз крутите барабан</div>
                </div>
            </div>
            <div class="rule">
                <div class="star">2</div>
                <div class="stext">
                    <div class="vstext">Випадає один з 6 секторів, кожен з яких має значення:</div>
                </div>
            </div>
        </div>
        <div class="peizes">
            <div class="peizesc">
                <div class="ico roza">Ви виграли 1 саджанець троянди</div>
                <div class="ico smile">Удача посмiхнеться вам наступного разу</div>
                <div class="ico vishnya">Ви виграли 1 саджанець чудо вишнi</div>
                <div class="smz"></div>
            </div>
            <div class="peizesc">
                <div class="ico mouse">Удача посмiхнеться вам наступного разу</div>
                <div class="ico malina">Ви виграли 1 саджанець малини</div>
                <div class="ico bird">Удача посмiхнеться вам наступного разу</div>
                <div class="smz"></div>
            </div>
        </div>
        <div class="rule" style="    margin-top: 6px;">
            <div class="star">3</div>
            <div class="stext">
                <div class="vstext">Кожному призу відповідає унікальний промокод, за допомогою якого ви зможете отримати свій подарунок
                </div>
            </div>
        </div>
    </div>

    <div id="played" style="display: none">


        <div class="pozdra"></div>
        <div class="vashv">ВИ ВИГРАЛИ:</div>
        <div class="prize"></div>
        <div class="instr">
            <div class="smz"></div>
            <div class="smz"></div>
            <div class="vpromo">Як отримати приз?</div>
            <div class="countdownt">Зробіть замовлення на сайті, поклавши в кошик будь-які товари, що вам сподобалися, на мінімальну суму від 700 гривень і введіть отриманий промокод в спеціальне поле. В кошик додасться виграний вами приз.</div>
        </div>
        <div class="cart"></div>
        <div class="podcart">
            <div class="txt1">Додайте товар у кошик <br/>та перейдiть в нього</div>
            <div class="txt2">Введiть промокод в поле <br/> "Ваш промо-код"</div>
            <div class="txt3">Отримайте <br/>подарунок</div>
        </div>
        <div class="vpromo2">Ваш промокод::</div>
        <div class="nadpromoco">
            <div class="promo"><?php echo $promocode; ?></div>
            <div class="copy">Скопiювати</div>

        </div>
        <input type="text" value="" class="promoi" style="display:none; position:absolute; left:-9999px; top: -999px;"/>
        <div class="countdownt">Промокод дійсний до::</div>
        <div class="countdown"></div>
        <div class="ps">Встигнiть <br/><span>отримати свiй приз!</span></div>
        <a class="shop_url" href="https://domicad.com.ua/ua/catalog"><span>В магазин</span></a>
    </div>
</div>
<div class="footer">
    <div class="copyright">2018 ПП «Твій дім і сад плюс» Офіційний сайт domicad.com.ua</div>
</div>
<img src="/application/views/promo/igra-sad-chudes/images/btn_active.png" class="needhide" style="display:none;"/>
<img src="/application/views/promo/igra-sad-chudes/images/btn_hover.png" class="needhide" style="display:none;"/>
<script src="/application/views/promo/igra-sad-chudes/js/jquery.min.js"></script>
<script src="/application/views/promo/igra-sad-chudes/js/jquery.fortune.js"></script>

<script src="/application/views/promo/igra-sad-chudes/js/jquery-ui.min.js"></script>
<script src="/application/views/promo/igra-sad-chudes/js/jquery.plugin.js"></script>
<script src="/application/views/promo/igra-sad-chudes/js/jquery.countdown.js"></script>
<script src="/application/views/promo/igra-sad-chudes/js/jquery.countdown-ru.js"></script>
<script>
    $('.needhide').show();
    $('.needhide').hide();

    var wins = {
        'malina': 'Саджанець малини',
        'vishnya': 'Саджанець чудо-вишнi',
        'roza': 'Саджанець троянди',
    };

    function stop_play(setcookie, pobeda) {
        if (setcookie) {
            setCookie('rlot2_played', Date.now());
            setCookie('rlot2_promo', pobeda)

        }

        var promo = getCookie('rlot2_promo')
        var c = wins[promo];
        var pomocod = '<?php echo $promocode?>';
        $('.promo').html(pomocod);
        $('.promoi').val(pomocod);
        $('.prize').html(c);

        setCookie('rlot2_promocod', pomocod);
        setCookie('rlot2_promocod_c', c);
        if (setcookie) {
            $('#not_played').fadeOut(500, function() {
                $('#played').fadeIn();
            });
        }
        else {
            $('#not_played').hide();
            $('#played').show();
        }
        $('.luchi').fadeOut();
        $('.frukti').fadeOut();

        $('.richag').addClass('disabled');

        // if (setcookie)
        //     $("html, body").animate({scrollTop: $('#played').offset().top}, 1000);


    }

    function start_play() {
        $('#not_played').show();
        $('#played').hide();
        $('.luchi').show();
        $('.frukti').show();
    }

    function getRandomInt(min, max) {
        return Math.floor(Math.random() * (max - min + 1)) + min;
    }


    $(function () {
        $('.play').hover();
        $('.countdown').countdown({until: new Date('20 December 2018 23:59:59')});
        var pobeda = '';
        if (getCookie('rlot2_played')) {
            stop_play(false, '');
        }
        else {
            start_play()
        }

        var win = <?php echo $winarray; ?>;
        console.log(win);

        var options = {
            prices: [
                {description: "roza"},
                {description: "mish"},
                {description: "malina"},
                {description: "ptica"},
                {description: "vishnya"},
                {description: "smile"},
            ],
            duration: 7000,
            // separation: 2,
            // min_spins: 10,
            // max_spins: 15,
            clockWise: true,
            prices_amount: 6, // The direction the wheel will spin
            // onSpinBounce: function () {
            //     Sounds.play('taka');
            // } // A callback to be called each time the roulette hits a price bound.
        };
        var $r = $('.roulette').fortune(options);
        var clickHandler = function () {
            $('.start').off('click');
            // $('.start').html('cdt');
            $r.spin(win).done(function (price) {
                setTimeout(function () {
                    // $('.start').prop('disabled', true).addClass('disabled')
                    setCookie('rlot2_played', 1);
                    stop_play(1, price.description)
                }, 2000);
            });
        };

        $('.start').on('click', clickHandler);


        var active = 0;

        $('.copy').click(function () {
            $('.promoi').show();
            $('.promoi').select();
            document.execCommand('copy');
            iosCopyToClipboard($('.promoi')[0])
            $('.promoi').hide();
            /*$('.promo').append(' ');
            $('.promo').val().slice(0, -1);*/
            // alert('Скопировано в буфер');
            // $(this).html('Скопировано')
            $(this).addClass('copied')
        });

    });

    function iosCopyToClipboard(el) {
        var oldContentEditable = el.contentEditable,
            oldReadOnly = el.readOnly,
            range = document.createRange();

        el.contenteditable = true;
        el.readonly = false;
        range.selectNodeContents(el);

        var s = window.getSelection();
        s.removeAllRanges();
        s.addRange(range);

        el.setSelectionRange(0, 999999); // A big number, to cover anything that could be inside the element.

        el.contentEditable = oldContentEditable;
        el.readOnly = oldReadOnly;

        document.execCommand('copy');
    }

    function setCookie(name, value) {
        var date = new Date();
        date.setTime(date.getTime() + (17 * 24 * 60 * 60 * 1000));
        var expires = "; expires=" + date.toGMTString();
        document.cookie = name + "=" + value + expires + "; path=/";
    }

    function getCookie(name) {
        var r = document.cookie.match("(^|;) ?" + name + "=([^;]*)(;|$)");
        if (r) return r[2];
        else return "";
    }

    function deleteCookie(name) {
        var date = new Date();
        date.setTime(date.getTime() - 1);
        document.cookie = name += "=; expires=" + date.toGMTString();
    }
</script>
<style>
    .bezp {
        margin-bottom: 20px;
    }
</style>
</body>
</html>
