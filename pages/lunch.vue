<template>
  <section id="menusection">
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
        english="Shredded pork & mustard vegetable"
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
        english="Beef stew & shrimp wonton"
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
        english="Beef Chow Fun (dry)"
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
        english="Shredded pork & mustard vegetable"
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

      <tr>
      <td>35.</td>
      <td><img src="/images/spicy.gif" width="13" height="18"></td>
      <td>Chicken w/ Eggplant in garlic Sauce
      &nbsp;
      茄子雞</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>36.</td>
      <td><img src="/images/spicy.gif" width="13" height="18"></td>
      <td>Kung Pao Chicken
      &nbsp; &nbsp; &nbsp; 
      宮保雞</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>37.</td>
      <td><img src="/images/spicy.gif" width="13" height="18"></td>
      <td>General Tso's Chicken
      &nbsp; &nbsp; &nbsp; 
      左宗雞</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>38.</td>
      <td></td>
      <td>Pork w/ Spinach
      &nbsp; &nbsp; &nbsp; 
      升瓜肉</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>39.</td>
      <td></td>
      <td>Roast Pork w/ Fresh Mushroom
      &nbsp;
      鮮菇叉燒</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>40.</td>
      <td></td>
      <td>Beijing Pork Chop
      &nbsp; &nbsp; &nbsp; 
      京都排骨</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>41.</td>
      <td></td>
      <td>Pork w/ Dry Bean Curd
      &nbsp; &nbsp; &nbsp; 
      香乾肉絲</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>42.</td>
      <td><img src="/images/spicy.gif" width="13" height="18"></td>
      <td>Twice Cooked Pork
      &nbsp; &nbsp; &nbsp; 
      回鍋肉</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>43.</td>
      <td><img src="/images/spicy.gif" width="13" height="18"></td>
      <td>Pork Garlic Sauce
      &nbsp; &nbsp; &nbsp; 
      魚香肉絲</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>44.</td>
      <td></td>
      <td>Pork Choop w/ Pepper Corn
      &nbsp; &nbsp; &nbsp; 
      椒鹽排</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>45.</td>
      <td></td>
      <td>Pork w/ Broccoli
      &nbsp; &nbsp; &nbsp; 
      芥蘭肉</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>46.</td>
      <td></td>
      <td>Pork w/ Mixed Vegetable
      &nbsp; &nbsp; &nbsp; 
      素菜肉</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>47.</td>
      <td></td>
      <td>Beef w/ Broccoil
      &nbsp; &nbsp; &nbsp; 
      芥蘭牛</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>48.</td>
      <td></td>
      <td>Beef w/ Mixed Vegetable
      &nbsp; &nbsp; &nbsp; 
      素菜牛</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>49.</td>
      <td></td>
      <td>Beef w/ Oyster Sauce
      &nbsp; &nbsp; &nbsp; 
      蠔油牛</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>50.</td>
      <td></td>
      <td>Beef / Pickle Mustard green
      &nbsp; &nbsp; &nbsp; 
      酸菜牛</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>51.</td>
      <td></td>
      <td>Pepper Steak
      &nbsp; &nbsp; &nbsp; 
      青椒牛</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>52.</td>
      <td><img src="/images/spicy.gif" width="13" height="18"></td>
      <td>Shreddeed Beef Country Style
      &nbsp; &nbsp; &nbsp; 
      干燒牛</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>53.</td>
      <td><img src="/images/spicy.gif" width="13" height="18"></td>
      <td>Shredded beef w/ Jalapeno Pepper
      &nbsp;
      小辣椒牛</td>
      <td align="right">6.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>54.</td>
      <td></td>
      <td>Kung Pao Baby Shrimp
      &nbsp; &nbsp; &nbsp; 
      宮保蝦仁</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>55.</td>
      <td></td>
      <td>Baby Shrimp w/ Bean Curd
      &nbsp; &nbsp; &nbsp; 
      豆腐蝦仁</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td colspan="2"></td>
      <td></td>
      <td></td>
      </tr>

      <tr>
      <td>56.</td>
      <td></td>
      <td>Baby Shrimp w/ Scrambled Egg
      &nbsp; &nbsp;
      蝦仁炒飯</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>57.</td>
      <td></td>
      <td>Calamari w/ Pickled Mustard Green
      &nbsp; &nbsp;
      酸菜鮮魷</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>58.</td>
      <td></td>
      <td>Baby Shrimp w/ Green Peas
      &nbsp; &nbsp; &nbsp; 
      清炒蝦仁</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>59.</td>
      <td></td>
      <td>Shrimp w/ Mixed Vegetables
      &nbsp; &nbsp; &nbsp; 
      什菜蝦球</td>
      <td align="right">8.95</td>
      </tr>
      
      <tr>
      <td>60.</td>
      <td></td>
      <td>Shrimp w/ Broccoli
      &nbsp; &nbsp; &nbsp; 
      芥蘭蝦球</td>
      <td align="right">8.95</td>
      </tr>

      <tr>
      <td>61.</td>
      <td></td>
      <td>Shrimp w/ Garlic Sauce
      &nbsp; &nbsp; &nbsp; 
      干燒牛</td>
      <td align="right">8.95</td>
      </tr>

      <tr>
      <td>62.</td>
      <td></td>
      <td>Shrimp w/ Lobster Sauce
      &nbsp; &nbsp; &nbsp; 
      蝦龍糊</td>
      <td align="right">8.95</td>
      </tr>

      <tr>
      <td>63.</td>
      <td></td>
      <td>Fish Fillet w/ Fresh Mushroom
      &nbsp; &nbsp;
      白菇班片</td>
      <td align="right">7.95</td>
      </tr>

      <tr>
      <td>64.</td>
      <td></td>
      <td>Fish Fillet w/ Chinese Green
      &nbsp; &nbsp; &nbsp; 
      菜遠班球</td>
      <td align="right">7.95</td>
      </tr>

      </table>

      <p><img src="/images/spicy.gif" width="13" height="18"> HOT & SPICY</p>

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
#menusection {
	margin-left: 50px;
}

.menucategory {
	font-weight: bold;
}

.menutable {
	margin-bottom: 1em;
	margin-top: 0.5em;
}
</style>

