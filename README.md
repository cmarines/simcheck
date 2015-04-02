<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, user-scalable=no">
  <link href="http://jqmdesigner.appspot.com/gk/lib/jquery.mobile/1.4.5/jquery.mobile-1.4.5.min.css" rel="stylesheet" type="text/css" />
  <script src="//ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
  <script src="//code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
  <!-- Uncomment the following to include cordova in your android project -->
  <!--<script src="http://jqmdesigner.appspot.com/platforms/android/cordova.js"></script>-->
  <!-- Export JS  -->
  <script>
    $(document).on('pageinit', function () {

      $('#hero_list li').click(function (e) {
        var heroName = $(this).text();
        console.log(heroName);
        $('#hero').text(heroName);
        var heroNum = $(this).index() + 1;
        $(".heroImg").hide();
        $("#hero" + heroNum).fadeIn(250);
      });

    });
  </script>
  <title>Check Sim</title>
</head>
<!-- script finish -->

<body>
<div id="home" data-role="page" style="background: url(http://www.cae.com/uploadedImages/Content/BusinessUnit/Corporate/News/2014/images/7000XR%20simulator.jpg) -80px 150px / 125% repeat repeat fixed;">
  <div data-role="header" data-position="fixed" data-theme="a">
    <h3>Check Sim</h3>
  </div>
  <div role="main" class="ui-content">
    <ul data-role="listview" data-inset="true" style="margin-top:0;">
      <li data-role="list-divider" style="margin:0 0 -10px 0; font-size:16px; background:-webkit-linear-gradient(#66f,#33a); text-shadow:none; color:#fff;">Select Resource</li>
    </ul>
    <ul data-role="listview" data-inset="true" id="hero_list" style="margin:0;">
      <li>
        <a href="#A310" data-transition="slide">
          <img src="http://icons.iconarchive.com/icons/aha-soft/standard-transport/256/plane-icon.png" class="ui-li-icon">A310 FFS</a>
      </li>
      <li>
        <a href="#B737" data-transition="slide">
          <img src="http://icons.iconarchive.com/icons/aha-soft/standard-transport/256/plane-icon.png" class="ui-li-icon">B737 FFS</a>
      </li>
      <li>
        <a href="#A310" data-transition="slide">
          <img src="http://icons.iconarchive.com/icons/aha-soft/standard-transport/256/plane-icon.png" class="ui-li-icon">A330 FFS</a>
      </li>
      <li>
        <a href="#B737" data-transition="slide">
          <img src="http://icons.iconarchive.com/icons/aha-soft/standard-transport/256/plane-icon.png" class="ui-li-icon">Q400 FFS</a>

      </li>
    </ul>
  </div>
</div>


<!--B737 FFS page -->
<div id="B737" data-role="page">
  <div data-role="header" data-position="fixed" data-theme="b">
    <h3>CheckList</h3>
    <a class="ui-btn ui-btn-left" style="-webkit-border-radius:20px;" href="#home" data-transition="slide" data-direction="reverse">Back</a>
  </div>
  <div role="main" class="ui-content">
    <fieldset data-role="controlgroup" data-type="vertical">
      <legend style="-webkit-border-radius:10px 10px 0 0; background:-webkit-linear-gradient(#99f,#33a); text-shadow:none; color:#fff; width:279px; height:30px; padding-top:7px; padding-left:10px; margin-bottom:-6px;">B737-800 FFS</legend>
      <input name="checkbox-b737-1" id="checkbox-b737-1" type="checkbox">
      <label for="checkbox-b737-1">IRS (x2)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-2" id="checkbox-b737-2" type="checkbox">
      <label for="checkbox-b737-2">DOME LIGHTS<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-3" id="checkbox-b737-3" type="checkbox">
      <label for="checkbox-b737-3">WINDOW HEAT<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-4" id="checkbox-b737-4" type="checkbox">
      <label for="checkbox-b737-4">PROBES<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-5" id="checkbox-b737-5" type="checkbox">
      <label for="checkbox-b737-5">CB LIGHTS<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-6" id="checkbox-b737-6" type="checkbox">
      <label for="checkbox-b737-6">AUX BAT<span style="float:right"><font color="blue">BAT</font></span></label>
      <input name="checkbox-b737-7" id="checkbox-b737-7" type="checkbox">
      <label for="checkbox-b737-7">WING ANTI-ICE<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-8" id="checkbox-b737-8" type="checkbox">
      <label for="checkbox-b737-8">ENGINE ANTI-ICE<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-9" id="checkbox-b737-9" type="checkbox">
      <label for="checkbox-b737-9">RECIRCULATION FAN<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-10" id="checkbox-b737-10" type="checkbox">
      <label for="checkbox-b737-10">STANDBY POWER<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-11" id="checkbox-b737-11" type="checkbox">
      <label for="checkbox-b737-11">EMERGENCY LIGHTS<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-12" id="checkbox-b737-12" type="checkbox">
      <label for="checkbox-b737-12">HYDRAULIC PUMPS(x4)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-13" id="checkbox-b737-13" type="checkbox">
      <label for="checkbox-b737-13">ENG BLEEDS<span style="float:right"><font color="green">ON</font></span></label>
      <input name="checkbox-b737-14" id="checkbox-b737-14" type="checkbox">
      <label for="checkbox-b737-14">FUEL PUMPS (x6)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-15" id="checkbox-b737-15" type="checkbox">
      <label for="checkbox-b737-15">APU GEN<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-16" id="checkbox-b737-16" type="checkbox">
      <label for="checkbox-b737-16">GEN 1 & 2<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-17" id="checkbox-b737-17" type="checkbox">
      <label for="checkbox-b737-17">PRESSURIZATION<span style="float:right"><font color="green">AUTO</font></span></label>
      <input name="checkbox-b737-18" id="checkbox-b737-18" type="checkbox">
      <label for="checkbox-b737-18">LANDING LIGHTS<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-19" id="checkbox-b737-19" type="checkbox">
      <label for="checkbox-b737-19">APU<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-20" id="checkbox-b737-20" type="checkbox">
      <label for="checkbox-b737-20">EXT LIGHTS<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-21" id="checkbox-b737-21" type="checkbox">
      <label for="checkbox-b737-21">LANDING GEAR Lever<span style="float:right"><font color="magenta">DOWN</font></span></label>
      <input name="checkbox-b737-22" id="checkbox-b737-22" type="checkbox">
      <label for="checkbox-b737-22">ALL DISPLAYS <span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-b737-23" id="checkbox-b737-23" type="checkbox">
      <label for="checkbox-b737-23">SPEED BRAKE<span style="float:right"><font color="red">STOWED</font></span></label>
      <input name="checkbox-b737-24" id="checkbox-b737-24" type="checkbox">
      <label for="checkbox-b737-24">FLAPS<span style="float:right"><font color="red">0</font></span></label>
      <input name="checkbox-b737-25" id="checkbox-b737-25" type="checkbox">
      <label for="checkbox-b737-25">PARKING BRAKE <span style="float:right"><font color="blue">SET</font></span></label>
      <input name="checkbox-b737-26" id="checkbox-b737-26" type="checkbox">
      <label for="checkbox-b737-26">CARGO FIRE<span style="float:right"><font color="blue">NORM</font></span></label>
      <input name="checkbox-b737-27" id="checkbox-b737-27" type="checkbox">
      <label for="checkbox-b737-27">ACP (audio control panel)<span style="float:right"><font color="red">ALL TO 0</font></span></label>
      <input name="checkbox-b737-28" id="checkbox-b737-28" type="checkbox">
      <label for="checkbox-b737-28">TCAS<span style="float:right"><font color="blue">STBY</font></span></label>
      <input name="checkbox-b737-29" id="checkbox-b737-29" type="checkbox">
      <label for="checkbox-b737-29">ADF 1 & 2<span style="float:right"><font color="blue">ADF</font></span></label>
      <input name="checkbox-b737-30" id="checkbox-b737-30" type="checkbox">
      <label for="checkbox-b737-30">LIGHTS<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-b737-31" id="checkbox-b737-31" type="checkbox">
      <label for="checkbox-b737-31">FLIGHT DIR. ( x2 )<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-32" id="checkbox-b737-32" type="checkbox">
      <label for="checkbox-b737-32">ENGINES<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-b737-33" id="checkbox-b737-33" type="checkbox">
      <label for="checkbox-b737-33">DC<span style="float:right"><font color="red">OFF</font></span></label>
    </fieldset>
  </div>
   <a class="ui-btn ui-btn-center" style="-webkit-border-radius:20px;" href="#home"data-transition="slide" data-direction="reverse">Save & Back</a>
</div>

<!--A310 FFS page -->
<div id="A310" data-role="page">
  <div data-role="header" data-position="fixed" data-theme="b">
    <h3>CheckList</h3>
    <a class="ui-btn ui-btn-left" style="-webkit-border-radius:20px;" href="#home" data-transition="slide" data-direction="reverse">Back</a>
  </div>
  <div role="main" class="ui-content">
    <fieldset data-role="controlgroup" data-type="vertical">
      <legend style="-webkit-border-radius:10px 10px 0 0; background:-webkit-linear-gradient(#99f,#33a); text-shadow:none; color:#fff; width:279px; height:30px; padding-top:7px; padding-left:10px; margin-bottom:-6px;">A310 FFS</legend>
      <input name="checkbox-A310-1" id="checkbox-A310-1" type="checkbox">
      <label for="checkbox-A310-1">LATERAL PANEL C/B LIGHTS<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-2" id="checkbox-A310-2" type="checkbox">
      <label for="checkbox-A310-2">IRS (x3)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-3" id="checkbox-A310-3" type="checkbox">
      <label for="checkbox-A310-3">OXYGEN LOW PRES. SUPPLY<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-4" id="checkbox-A310-4" type="checkbox">
      <label for="checkbox-A310-4">APU<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-5" id="checkbox-A310-5" type="checkbox">
      <label for="checkbox-A310-5">EXT POWER<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-6" id="checkbox-A310-6" type="checkbox">
      <label for="checkbox-A310-6">FUEL(OUTR,INR,CTR)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-7" id="checkbox-A310-7" type="checkbox">
      <label for="checkbox-A310-7">PROBE HEAT (x3)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-8" id="checkbox-A310-8" type="checkbox">
      <label for="checkbox-A310-8">WINDOW HEAT (x2)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-9" id="checkbox-A310-9" type="checkbox">
      <label for="checkbox-A310-9">PACK VLV #1<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-10" id="checkbox-A310-10" type="checkbox">
      <label for="checkbox-A310-10">DOME LIGHTS<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-11" id="checkbox-A310-11" type="checkbox">
      <label for="checkbox-A310-11">EXT LT<span style="float:right"><font color="red">ALL OFF</font></span></label>
      <input name="checkbox-A310-12" id="checkbox-A310-12" type="checkbox">
      <label for="checkbox-A310-12">APU MASTER SWITCH)<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-13" id="checkbox-A310-13" type="checkbox">
      <label for="checkbox-A310-13">EMER EXT LT<span style="float:right"><font color="red">ON</font></span></label>
      <input name="checkbox-A310-14" id="checkbox-A310-14" type="checkbox">
      <label for="checkbox-A310-14">PFD & ND<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-15" id="checkbox-A310-15" type="checkbox">
      <label for="checkbox-A310-15">ILS switch<span style="float:right"><font color="blue">NAV</font></span></label>
      <input name="checkbox-A310-16" id="checkbox-A310-16" type="checkbox">
      <label for="checkbox-A310-16">FD/FPV<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-17" id="checkbox-A310-17" type="checkbox">
      <label for="checkbox-A310-17">AUTOPILOT<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-18" id="checkbox-A310-18" type="checkbox">
      <label for="checkbox-A310-18">LANDING GEAR Lever<span style="float:right"><font color="magenta">Down</font></span></label>
      <input name="checkbox-A310-19" id="checkbox-A310-19" type="checkbox">
      <label for="checkbox-A310-19">MCDUs (FMS)<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-20" id="checkbox-A310-20" type="checkbox">
      <label for="checkbox-A310-20">SPEED BRAKE<span style="float:right"><font color="red">RETRACTED</font></span></label>
      <input name="checkbox-A310-21" id="checkbox-A310-21" type="checkbox">
      <label for="checkbox-A310-21">FLAP LEVER<span style="float:right"><font color="red">0</font></span></label>
      <input name="checkbox-A310-22" id="checkbox-A310-22" type="checkbox">
      <label for="checkbox-A310-22">PARKING BRAKE<span style="float:right"><font color="blue">SET</font></span></label>
      <input name="checkbox-A310-23" id="checkbox-A310-23" type="checkbox">
      <label for="checkbox-A310-23">LEFT & RIGHT DISPLAY<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-24" id="checkbox-A310-24" type="checkbox">
      <label for="checkbox-A310-24">LT PFD & OVHD PANEL<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-25" id="checkbox-A310-25" type="checkbox">
      <label for="checkbox-A310-25">PFD & OVHD FLOOD<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-26" id="checkbox-A310-26" type="checkbox">
      <label for="checkbox-A310-26">FLOOD & READING LIGHTS<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-27" id="checkbox-A310-27" type="checkbox">
      <label for="checkbox-A310-27">CAPTN & CTR LIGHTS<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-28" id="checkbox-A310-28" type="checkbox">
      <label for="checkbox-A310-28">CAPT + FO + Center instruments lights<span style="float:right"><font color="red">DIM</font></span></label>
      <input name="checkbox-A310-29" id="checkbox-A310-29" type="checkbox">
      <label for="checkbox-A310-29">ENGINES<span style="float:right"><font color="red">OFF</font></span></label>
      <input name="checkbox-A310-30" id="checkbox-A310-30" type="checkbox">
      <label for="checkbox-A310-30">BATT. (x3)<span style="float:right"><font color="red">OFF</font></span></label>
    </fieldset>
  </div>
   <a class="ui-btn ui-btn-center" style="-webkit-border-radius:20px;" href="#home"data-transition="slide" data-direction="reverse">Save & Back</a>
</div>

</body>

</html>

