# Shuriken-Blinky-Board
What my project is: A custom built blinky board in the shape of a Shuriken with a custom 3D printed case!

What it does: The shuriken blinky board lights up Red LEDs like an LED chaser, which is an electronic circuit that lights up a string of LEDs in a sequential, moving pattern to create a visually appealing "chasing" effect.

Why it exists: Similar to how we learn the basics of programming by printing out, "Hello World", the blinky board acts as an introduction for individuals into the world of hardware. Additionally, Blinky boards are fun because they provide an extremely rewarding, basic introduction to electronics, Cad modelling,ne and soldering!
As stated above, unlike other blinky boards, this one comes with a 3D printed case to cover it from dust and other foreign substances. I have a dog at home so I say this by experience: A CASE IS NEEDEDDDD!

The Schematic for the Blinky Board:

<img width="1384" height="974" alt="Screenshot 2026-05-24 152341" src="https://github.com/user-attachments/assets/e476b7e1-e0f7-410d-bead-9808065d57c1" />


Final Model of blinky board:

<img width="975" height="851" alt="Screenshot 2026-05-26 195212" src="https://github.com/user-attachments/assets/7f69d543-db9c-4437-988d-36baff93e5a2" />


3D printed Case:

<img width="1229" height="896" alt="Screenshot 2026-05-26 195357" src="https://github.com/user-attachments/assets/dd9d2f1d-0d36-42de-a6b3-eecf1763869e" />

How to make it:

Order the pcb from a manufacturer and solder the given components in the BOM table below as per the above picture of the final model of the blinky board.
Additionally, 3D print the case in the CAD file with the main case and the supporting cover. 


Bill of Materials:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h2>Bill of Materials</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Cost of 1</th>
                <th>Total</th>
                <th>Link</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>3D Print</td>
                <td>$5.00</td>
                <td>$5.00</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>PCB</td>
                <td>$9.41</td>
                <td>$9.41</td>
                <td>N/A</td>
            </tr>
            <tr>
                <td>NE555P</td>
                <td>$0.27</td>
                <td>$0.27</td>
                <td><a href="https://robu.in/product/ne555p-texas-instruments-timer-single-precision-100-khz-pdip-8/" target="_blank">View Item</a></td>
            </tr>
            <tr>
                <td>CD4017</td>
                <td>$0.30</td>
                <td>$0.30</td>
                <td><a href="https://electronicspices.com/product/cd4017-decade-counter-ic-dip-16-package?srsltid=AfmBOopc3RXAm-_MzwVCcUROpGEU86FgFGkNwRUev5t1WDMeklrVmSgAsHM" target="_blank">View Item</a></td>
            </tr>
            <tr>
                <td>Header Pins</td>
                <td>$0.12</td>
                <td>$0.12</td>
                <td><a href="https://robu.in/product/2-54mm-1x40-pin-female-single-row-header-strip-pack-of-10/" target="_blank">View Item</a></td>
            </tr>
            <tr>
                <td>Capacitor</td>
                <td>$0.031</td>
                <td>$0.031</td>
                <td><a href="https://quartzcomponents.com/products/50v-1uf-electrolytic-capacitor?variant=35154623561881&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOoq-fjQ5PZyQOrdlzf2Xx5gWJC7Jn8dRuM75eLHuA7vDqyDkl5yVuE0" target="_blank">View Item</a></td>
            </tr>
            <tr>
                <td>Polarized Capacitor</td>
                <td>$0.0086</td>
                <td>$0.0086</td>
                <td><a href="https://smartxprokits.in/103pf-ceramic-capacitor/?srsltid=AfmBOooTa2XfHi2bumZzZo_GUhJyFTN57lBgKVt_ZQqWNbcnqv1YD6YDXe4" target="_blank">View Item</a></td>
            </tr>
            <tr>
                <td>Resistor</td>
                <td>$0.010</td>
                <td>$0.010</td>
                <td><a href="https://www.flyrobo.in/planetary-geared-motor-24v-175rpm-100w?tracking=ads&srsltid=AfmBOoq6mzx2vakF22ijog7EjLSd7ayoshEE8mTJCbD0Y41k4Xgby_H3TS0" target="_blank">View Item</a></td>
            </tr>
            <tr>
                <td>Variable Resistor</td>
                <td>$0.10</td>
                <td>$0.10</td>
                <td><a href="https://quartzcomponents.com/products/1k-ohm-0-5w-102-multiturn-variable-resistor-trimpot-trimmer?variant=44022273409258&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOooTCVVf6EZ7no0GNhUNw94ewehk1EcFQkbeMPzzqV8PMHDoRCDFJK8" target="_blank">View Item</a></td>
            </tr>
            <tr>
                <td>Red LED</td>
                <td>$0.10</td>
                <td>$0.10</td>
                <td><a href="https://harishprojects.com/products/5mm-red-led-pack-of-10?variant=46761597010098&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AfmBOooB_5NcGDLodXrF2aRzwCUuEw4afQGS7NZa-P1TkYbdikbXJ0-cGmo" target="_blank">View Item</a></td>
            </tr>
        </tbody>
        <tfoot>
            <tr class="total-row">
                <td colspan="2" style="text-align: right;">Grand Total:</td>
                <td>$15.3496</td>
                <td></td>
            </tr>
        </tfoot>
    </table>

</body>
</html>

Zine:

<img width="652" height="1006" alt="image" src="https://github.com/user-attachments/assets/c9624847-be86-463b-9dd0-5e3abbced74a" />
