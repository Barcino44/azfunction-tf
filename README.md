## Documentation

First, it was neccesary to log in to the azure CLI using thw student account.

<p align="center">
  <img width="1089" height="421" alt="image" src="https://github.com/user-attachments/assets/82a5564a-e20e-4742-a788-9d2ed454492a" />
</p>
After that, it was initialized terraform using the command.

````
terraform init
````
Once that was done, the next thing I did was check the indentation using the command.

````
terraform fmt
````
Then, it was checked the HCL code in order to discover missing features required to build the function.

To do that, it was used the following command.
````
terraform plan
````

In this case, we discover it was neccesary to add the subscriptionId in the definition of the provider.

<p align="center">
  <img width="519" height="132" alt="image" src="https://github.com/user-attachments/assets/a1b25d3f-fdf5-4bad-8a64-a968d1292101" />
</p>

After reviewing that all the code is clean, we execute the command.

````
terraform apply
````

And we add a name to the function which is going to be created.

<p align="center">
  <img width="573" height="110" alt="image" src="https://github.com/user-attachments/assets/266c2bc6-a7fc-4baa-9eb3-19ed6e5cce30" />
</p>

We confirm the actions related with the creation of the function.

<p align="center">
  <img width="517" height="129" alt="image" src="https://github.com/user-attachments/assets/e76c55b7-6607-4dd5-afd1-43d3777120f7" />
</p>

Finally we access to the web site to see if the function was created successfully.

<p align="center">
  <img width="1242" height="138" alt="image" src="https://github.com/user-attachments/assets/c4a0e131-5917-4e76-91cd-c58887b6da88" />
</p>

And we can go to the azure portal to see the resources created.

<p align="center">
  <img width="1509" height="650" alt="image" src="https://github.com/user-attachments/assets/2a1530f9-7de5-447a-8b38-e0fe6a32da8a" />
</p>

