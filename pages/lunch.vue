<template>
  <section id="menusection" class="pt-5">
    <div class="row justify-content-center"
      <span class="menucategory">Served From Monday - Friday : 11:00 am - 3:00 pm Except Holidays
      &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <br /><br />
      Noodle Soup with Lo Mein, Chow Fun Noodle & Fried Rice</span>

      <table class="menutable" border="0">

        <LunchItem
          number="1"
          :spicy="false"
          english="Mixed Vegetable"
          chinese="蔬菜湯麵"
          price="5.95"
        />

        <LunchItem
          number="2"
          :spicy="true"
          english="Shredded Pork & Mustard Vegetable"
          chinese="榨菜肉絲湯麵"
          price="5.95"
        />

        <LunchItem
          number="3"
          :spicy="false"
          english="Shrimp Wonton"
          chinese="鮮蝦雲吞湯麵"
          price="5.95"
        />

        <LunchItem
          number="4"
          :spicy="false"
          english="Beef Stew"
          chinese="牛腩湯麵"
          price="6.95"
        />

        <LunchItem
          number="5"
          :spicy="false"
          english="Sliced Beef"
          chinese="牛肉湯麵"
          price="6.95"
        />

        <LunchItem
          number="6"
          :spicy="false"
          english="Beef Stew & Shrimp Wonton"
          chinese="牛腩雲吞湯"
          price="7.95"
        />

        <LunchItem
          number="7"
          :spicy="false"
          english="Jumbo Shrimp"
          chinese="蝦球湯麵"
          price="8.95"
        />

        <LunchItem
          number="8"
          :spicy="false"
          english="Seafood"
          chinese="海鲜湯"
          price="8.95"
        />

        <LunchItem
          number="9"
          :spicy="false"
          english="Vegetable Mei Fun"
          chinese="蔬菜米粉"
          price="5.95"
        />

        <LunchItem
          number="10"
          :spicy="false"
          english="Harmen Mei Fun"
          chinese="廈門米粉"
          price="6.95"
        />

        <LunchItem
          number="11"
          :spicy="false"
          english="(Tai Pan) Home Style Mei Fun"
          chinese="大鵬米粉"
          price="6.95"
        />

        <LunchItem
          number="12"
          :spicy="true"
          english="Singapore Mei Fun"
          chinese="星洲米粉"
          price="6.95"
        />

        <LunchItem
          number="13"
          :spicy="true"
          english="Beef Chow Fun (Dry)"
          chinese="干炒牛河粉"
          price="6.95"
        />

        <LunchItem
          number="14"
          :spicy="false"
          english="Chicken Chow Fun"
          chinese="雞炒河粉"
          price="6.95"
        />

        <LunchItem
          number="15"
          :spicy="true"
          english="Shrimp Chow Fun"
          chinese="蝦炒河粉"
          price="6.95"
        />

        <LunchItem
          number="16"
          :spicy="false"
          english="Pork Chow Fun"
          chinese="肉炒河粉"
          price="6.95"
        />

        <LunchItem
          number="17"
          :spicy="false"
          english="Chicken Lo Mein"
          chinese="雞撈麵"
          price="6.95"
        />

        <LunchItem
          number="18"
          :spicy="false"
          english="Shrimp Lo Mein"
          chinese="蝦撈麵"
          price="6.95"
        />

        <LunchItem
          number="19"
          :spicy="false"
          english="Beef Lo Mein"
          chinese="牛肉撈麵"
          price="6.95"
        />

        <LunchItem
          number="20"
          :spicy="false"
          english="Pork Lo Mein"
          chinese="肉撈麵"
          price="6.95"
        />

        <LunchItem
          number="21"
          :spicy="false"
          english="House Special Lo Mein"
          chinese="本樓撈麵"
          price="6.95"
        />

        <LunchItem
          number="22"
          :spicy="false"
          english="Chicken or Pork Fried Rice"
          chinese="雞或肉炒飯"
          price="5.95"
        />

        <LunchItem
          number="23"
          :spicy="false"
          english="Shrimp or Beef Fried Rice"
          chinese="蝦或牛肉炒飯"
          price="6.95"
        />

        <LunchItem
          number="24"
          :spicy="false"
          english="House Special Fried Rice"
          chinese="本樓炒飯"
          price="6.95"
        />

        <LunchItem
          number="25"
          :spicy="false"
          english="Young Chow Fried Rice"
          chinese="揚州炒飯"
          price="6.95"
        />

        <LunchItem
          number="26"
          :spicy="false"
          english="Chicken Broccoli"
          chinese="芥蘭雞"
          price="7.95"
        />

        <LunchItem
          number="27"
          :spicy="false"
          english="Chicken w/ Mixed Vegetables"
          chinese="素菜雞"
          price="7.95"
        />

        <LunchItem
          number="28"
          :spicy="true"
          english="Chicken w/ Garlic Sauce"
          chinese="魚香雞"
          price="7.95"
        />

        <LunchItem
          number="29"
          :spicy="false"
          english="Chicken w/ Cashew Nuts"
          chinese="腰果雞"
          price="7.95"
        />

        <LunchItem
          number="30"
          :spicy="false"
          english="Shredded Pork & Mustard Vegetable"
          chinese="榨菜肉絲湯麵"
          price="7.95"
        />

        <LunchItem
          number="31"
          :spicy="true"
          english="Chicken w/ Curry Sauce"
          chinese="咖哩雞"
          price="7.95"
        />

        <LunchItem
          number="32"
          :spicy="false"
          english="Chicken w/ String Bean"
          chinese="四季豆雞"
          price="7.95"
        />

        <LunchItem
          number="33"
          :spicy="false"
          english="Sesame Chicken"
          chinese="芝麻雞"
          price="7.95"
        />

        <LunchItem
          number="34"
          :spicy="false"
          english="Chicken w/ Chinese Broccoli"
          chinese="唐芥蘭雞"
          price="7.95"
        />

        <LunchItem
          number="35"
          :spicy="true"
          english="Chicken w/ Eggplant in Garlic Sauce"
          chinese="茄子雞"
          price="7.95"
        />

        <LunchItem
          number="36"
          :spicy="true"
          english="Kung Pao Chicken"
          chinese="宮保雞"
          price="7.95"
        />

        <LunchItem
          number="37"
          :spicy="true"
          english="General Tso's Chicken"
          chinese="左宗雞"
          price="7.95"
        />

        <LunchItem
          number="38"
          :spicy="false"
          english="Pork w/ Spinach"
          chinese="升瓜肉"
          price="7.95"
        />

        <LunchItem
          number="39"
          :spicy="false"
          english="Roast Pork w/ Fresh Mushroom"
          chinese="鮮菇叉燒"
          price="7.95"
        />

        <LunchItem
          number="40"
          :spicy="false"
          english="Beijing Pork Chop"
          chinese="京都排骨"
          price="7.95"
        />

        <LunchItem
          number="41"
          :spicy="false"
          english="Pork w/ Dry Bean Curd"
          chinese="香乾肉絲"
          price="7.95"
        />

        <LunchItem
          number="42"
          :spicy="true"
          english="Twice Cooked Pork"
          chinese="回鍋肉"
          price="7.95"
        />

        <LunchItem
          number="43"
          :spicy="true"
          english="Pork Garlic Sauce"
          chinese="魚香肉絲"
          price="7.95"
        />

        <LunchItem
          number="44"
          :spicy="false"
          english="Pork Chop w/ Peppercorn"
          chinese="椒鹽排"
          price="7.95"
        />

        <LunchItem
          number="45"
          :spicy="false"
          english="Pork w/ Broccoli"
          chinese="芥蘭肉"
          price="7.95"
        />

        <LunchItem
          number="46"
          :spicy="false"
          english="Pork w/ Mixed Vegetable"
          chinese="素菜肉"
          price="7.95"
        />

        <LunchItem
          number="47"
          :spicy="false"
          english="Beef w/ Broccoli"
          chinese="芥蘭牛"
          price="7.95"
        />

        <LunchItem
          number="48"
          :spicy="false"
          english="Beef w/ Mixed Vegetable"
          chinese="素菜牛"
          price="7.95"
        />

        <LunchItem
          number="49"
          :spicy="false"
          english="Beef w/ Oyster Sauce"
          chinese="蠔油牛"
          price="7.95"
        />

        <LunchItem
          number="50"
          :spicy="false"
          english="Beef w/ Pickled Mustard Greens"
          chinese="酸菜牛"
          price="7.95"
        />

        <LunchItem
          number="51"
          :spicy="false"
          english="Pepper Steak"
          chinese="青椒牛"
          price="7.95"
        />

        <LunchItem
          number="52"
          :spicy="true"
          english="Shredded Beef Country Style"
          chinese="干燒牛"
          price="7.95"
        />

        <LunchItem
          number="53"
          :spicy="true"
          english="Shredded Beef w/ Jalapeno Pepper"
          chinese="小辣椒牛"
          price="6.95"
        />

        <LunchItem
          number="54"
          :spicy="false"
          english="Kung Pao Baby Shrimp"
          chinese="宮保蝦仁"
          price="7.95"
        />

        <LunchItem
          number="55"
          :spicy="false"
          english="Baby Shrimp w/ Bean Curd"
          chinese="豆腐蝦仁"
          price="7.95"
        />

        <LunchItem
          number="56"
          :spicy="false"
          english="Baby Shrimp w/ Scrambled Egg"
          chinese="蝦仁炒飯"
          price="7.95"
        />

        <LunchItem
          number="57"
          :spicy="false"
          english="Calamari w/ Pickled Mustard Greens"
          chinese="酸菜鮮魷"
          price="7.95"
        />

        <LunchItem
          number="58"
          :spicy="false"
          english="Baby Shrimp w/ Green Peas"
          chinese="清炒蝦仁"
          price="7.95"
        />

        <LunchItem
          number="59"
          :spicy="false"
          english="Shrimp w/ Mixed Vegetables"
          chinese="什菜蝦球"
          price="8.95"
        />

        <LunchItem
          number="60"
          :spicy="false"
          english="Shrimp w/ Broccoli"
          chinese="芥蘭蝦球"
          price="8.95"
        />

        <LunchItem
          number="61"
          :spicy="false"
          english="Shrimp w/ Garlic Sauce"
          chinese="干燒牛"
          price="8.95"
        />

        <LunchItem
          number="62"
          :spicy="false"
          english="Shrimp w/ Lobster Sauce"
          chinese="蝦龍糊"
          price="8.95"
        />

        <LunchItem
          number="63"
          :spicy="false"
          english="Fish Fillet w/ Fresh Mushroom"
          chinese="白菇班片"
          price="7.95"
        />

        <LunchItem
          number="64"
          :spicy="false"
          english="Fish Fillet w/ Chinese Greens"
          chinese="菜遠班球"
          price="7.95"
        />

      </table>

      <p><img src="~/assets/images/spicy.gif" width="13" height="18"> HOT & SPICY</p>

      <p>If you would like something and do not see it on our menu, please ask us.</p>

      </div>
    </div>
  </section>
</template>

<script>
import LunchItem from '../components/LunchItem.vue';

export default {
  name: 'lunch',
  components: { LunchItem }
}
</script>

<style scoped>
@media (min-width: 768px) {
  #menusection { margin-left: 100px; }
}

.menucategory {
	font-weight: bold;
}

.menutable {
	margin-bottom: 1em;
	margin-top: 0.5em;
}

img {
  padding-bottom: 4px;
}
</style>

