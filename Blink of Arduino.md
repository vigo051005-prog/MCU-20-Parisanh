# Let's start
If you look at your microcontroller board, you'll notice that there's no easy way to plug

in a monitor, which makes writing the phrase Hello World as a first program actually quite difficult.

When it comes to programming microcontrollers, there is a first program we can write that is quite simple and it tests functionality.

> [!NOTE] Title
> ສິ່ງທີ່ພວກເຮົາຕ້ອງເຮັດກໍຄື ເຮັດໃຫ້ LED ກະພິບ.

## Demonstration (How it works)

**What Happens**

- 1. The LED turns on for 1 second.
    
    ![digitalWrite(LED_BUILTIN, HIGH);
    delay(1000);](https://prod-files-secure.s3.us-west-2.amazonaws.com/079bf8a3-06ec-4b0a-aad8-7f5c1f84e1e8/f29303b9-a0ff-47e1-ad13-34fa448793fb/1._Experiment_Blink.png)
    
    ```
    digitalWrite(LED_BUILTIN, HIGH);
    delay(1000);
    ```
    
- 2. The LED turns off for 1 second.
    
    ![digitalWrite(LED_BUILTIN, LOW);
    delay(1000);](https://prod-files-secure.s3.us-west-2.amazonaws.com/079bf8a3-06ec-4b0a-aad8-7f5c1f84e1e8/fb23120f-7525-42ee-ad0c-d62dce34f204/1._Experiment_Blink_\(1\).png)
    
    digitalWrite(LED_BUILTIN, LOW);  
    delay(1000);
    

1. This cycle repeats indefinitely, making the LED blink.