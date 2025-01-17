# Combat Rewards

## Stamina per Fight

The total amount of stamina consumed after each fight is entirely depend on players’ determination, which can be exerted up to 200 per fight.  

Gas offset is only charged once per transaction. Accordingly, players are likely to be awarded average reward baseline which can be worth 5 times as much as their expectation if they deem to use up 200 stamina, but only once-off for gas offset.

The fees imposed on stamina consumption are on the par with the estimated increase in dollar value while valuating the gas fees. Having said that profits reaped per fight might be unsteady after an average period of time if players lose several high stamina fights.

Combat experience is also multiplied equivalently based on the value of stamina players pick out. 

## xWeapon Payout

Below is the formula to calibrate xWeapon payout:

$$
payout = gasOffset + (baseline * √(enemyPower/1000))
$$

Gas Offset is shown in the earnings calculator as follows:

![image](https://user-images.githubusercontent.com/90205972/135366545-5f55137c-a95d-4d65-b41f-abf584c59af2.png)

Baseline is also shown in the earnings calculator as follows:

![image](https://user-images.githubusercontent.com/90205972/135366554-bd0fc729-58ce-4770-b69e-ffacb7c676b1.png)

These numbers are appropriately modified by the Oracle which covers the currency value of xWeapon

{% hint style="info" %}
Please note that the “power” variable manifested in the above formula refers to the listed power value of whichever enemy players prefer to engage in the battles. 
{% endhint %}

