![image](https://github.com/petriQore/CreativeMinds-2024-Qualifier-CTF/assets/123587287/9312c19b-8d06-4df0-8abd-3088d9395821)

<br>

Obviously we can't decrypt the grades without the key, so let's take a look at how keys are generated

<br>

![image](https://github.com/petriQore/CreativeMinds-2024-Qualifier-CTF/assets/123587287/836d9cb5-fcd7-44ee-8163-f51389372512)

<br>

So the key is generated using a random int in the range of (0, 0xff), and we can exploit that by bruteforce since there is a finite and small amount of keys that can be generated that way.

<br>

![image](https://github.com/petriQore/CreativeMinds-2024-Qualifier-CTF/assets/123587287/349c5bcb-7ea5-4f42-bc63-d160f5fa1c95)

![image](https://github.com/petriQore/CreativeMinds-2024-Qualifier-CTF/assets/123587287/d0383394-1d8c-4670-974f-4745ff3db075)
