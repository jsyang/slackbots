# Pepe (Roni) bot ?

## Live by the pie, die by the pie

- https://www.facebook.com/hoxton.olive

- Begins a 30 minute interactive session collecting pizza orders for Olive
    - Identify base pizza
    - Identify toppings
    - Calculate total for person

- Can also notify all people who have ordered pizza when pizza's arrived and where

- After session has ended and order's been sent
```
    anybody                 : "pizza's here on the first floor" (trigger)
    pepe                    : "do you want me to PM everyone?"
    triggering slack user   : "yes"

    (person 1 gets PM "pizza's here on the first floor")
    (person 2 get PM ...)
    ... etc.

# Pepe.birth()

```bash
cd Pepe
npm start
```
# Known issues

- Pepperoni orders have an unintended extra pepperoni topping
- Multiple pizza order not yet supported / detected
