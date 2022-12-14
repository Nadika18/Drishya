# Team PNP | दृश्य

## Problem Statement

Vision plays an important role in the daily life of a person. From getting up to start the day, until ending it, eyes are the most important organs of our body. Unfortunately some people are not able to see this beautiful world. Visually impared people can’t easily recognize obstacles or stairs while using normal blind stick. They struggle with their day to day life and everyday activities.

![blind stick](https://thumbs.dreamstime.com/b/closed-eyes-icon-white-background-black-flat-line-art-isolated-155579255.jpg)

The blind traveler should
depend on any other guide like blind cane , people information , trained dogs, etc. About the **90% of the worlds visually
impaired live in developing countries**. No safety features are present on the normal blind stick which is mostly used by visually impaired people for their visual aid.

# Proposed Solution

Now there are other technical solution like Smart Blind Stick using sonic sensors and other components but these solutions still have many disadvantages for example; They cant detect obstructions that are hidden but very dangerous for the blind such as downward stairs, holes etc. Usually, the feedback information comes out as either vibration or sound signals. Our solution is to develop a smart glass which is not unlike any other smart glasses.

![Headphones](https://media1.giphy.com/media/enUXK8X9kZkvcBTUur/giphy.gif?cid=790b761102ff1283dcd2cd7045e20fd12fb69f5ee7218baf&rid=giphy.gif&ct=g)

This smart glasses will be developed for those users who are visually impaired and have difficulty regarding their vision. Our device will not only be able to predict the objects but also find their location in terms of bounding boxes. The impaired person will be provided with the information through speakers that would be attached to their smart glasses. The bounding boxes in the field of view of the camera will be entertained to the ears of the user with a simple location based quadrant mapping with a central field. If an object is in any of these location, it's position along with the object type will be played through the speakers. This enables the user to be conscious about their surroundings.

## How do we priortize incase of multiple objects in the FOV?

We use the following algorithm to choose the best object in the scene:

![aiming](https://media1.giphy.com/media/xT5LMsfrTiHCzLG0A8/giphy.gif?cid=ecf05e47g1wbskk1d7sdrldjfld2lfanrg4brnr6e1oti3aq&rid=giphy.gif&ct=g)

- Objects in the center of the field are more prone to be selected because we set a focal point straight infront of the glasses (the focus shifts with the movement of the user's head),
- The objects with bigger bounding box are then given more priority as it results to closer objects,
- Bounding box with higher prediction score have some weight in which final box is to be selected.

## How do we aid user to direct towards the detected object ?

The FOV is divided into 5 regions that distinctly distinguish where the object is. This can be clearly seen in the image below.

![quadrant_view](https://media.discordapp.net/attachments/1032654825382490167/1040959329664241664/image.png?width=448&height=388)

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.


Each region is logically divided in the view of user wearing the device. Here,  ***L*** refers to **left** from the user's view, ***R*** refers to **right** from the user's view, ***T*** refers to **top** from the user's view, ***B*** refers to **bottom** from the user's view and ***C*** refers to **center** from the user's view. A combination of any of them maps them to a particular region in the FOV.

<br>
<br>


# Cost Calculation

### Starter Kit

| **Device**              | **Cost(In USD)**  |
|-------------------------|-------------------|
| Coral TPU               | $19               |
| ESP-32 Camera           | $8                |
| Fabrication and Custom Glasses with speaker | $7                |
| Battery                 | $5                |
| **Total**               |  $39              |

<br>

## Mass Production Estimated Cost


| **Device**              | **Cost(In USD)**  |
|-------------------------|-------------------|
| Rockchip RK3588         | $50               |
| IMX 766                 | $20               |
| Fabrication and Custom  | $15               |
| Glasses with speaker    | $3                |
| NAND and RAM            | $17               |
| Battery                 | $15               |
| **Total**               | $100              |

<br>

# Power Calculation


| **Device**              | **Current**  | **Voltage**   | **Power**          |
|-------------------------|--------------|---------------|--------------------|
| Coral TPU @ 2T Flops    | 0.303        | 3.3           | 1W                 |
| ESP-32 Camera           | 0.18         | 5             | 0.9                |
| Battery                 | 0.2          | 5             | 1 W                |
| **Total**               |              |               | 2.9W               |

<br>

# Usage Time

|  **Capacity**           | **Voltage**  | **Watt Hour** | **Time in hours**  |
|-------------------------|--------------|---------------|--------------------|
|  2000Mah                | 4.2          | 8.4           | 2.87               |
|  3000Mah                | 4.2          | 12.6          | 4.34               |


# Research and Development Accounting

- Assets:
    Devices bought in product design.
    $2000 worth of devices to assist and aid in design.

- Computer Resource:
    Training the neural network for better prediction of objects.
    $9285 for 730 hours of training in google cloud platform.

- Wages:
    With a workforce of 4 people, contributing to total expense of $300 for
    each month for each person. The total expense for 3 month product development in wages 
    results to $4500.

# Mass Production of Device.

$40 per device. The starter kit will go in production after 3 month of
development. The initial sale will count upto 3000 devices. Marking a profit
margin of $20 per device, we can sale the device @ $60 per user. This counts to 
$20 * 3000 = $60000 of estimated income if all the devices bear sale.

We are open to investment and backer who could further assist to make our
product profitable.

The $20 margin over the product is a bit high, but every device we sale comes
with a warrenty span of 2 years, which will cover any type of accidental damage.

# Initial Investment

3000 devices costing each $40 to paid at once summing to $120000, and $2000 prototype materials,
$10000 in AI training, $4500 for wages, $2000 for security deposit. Marketing
Cost may include $2000 based on the interest and type of marketing.

So the total sum accounts to $140500.

# Recovering the Capital

Initial Investment goal sums to $30000.
Early Adopter discount for first 1000 devices costing $55.
If all the 1000 devices are sold, this accounts to $55000.

This initial sum amounts to $85,000 which we can pay to advance to production of
our 3000 units.
The sum will not be paid in total to the manufacture our device. Remaining
payment shall in later installments.

Considering the remaining units to be sold. We earn about $60 * 2000 = $120000.

Remaining Manufacture Cost: $120000 - (paid) $70000 = $50000
Marketing and Operating Cost: $5000

Operating Cost is Covered by the remaining initial $15000 to fuel the company for 6
months.

The target is to sell 2000/6 ~ 334 units to sold per month.
If this target is met, $50000/60 = 667 units to be sold to recover the capital.
