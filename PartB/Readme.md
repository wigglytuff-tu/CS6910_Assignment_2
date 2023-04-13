## Part B
1. Notebook is structured such that it can be run cell by cell to train InceptionV3
2. Please mention the full path to respective directories as
```
train_dir = "/content/drive/MyDrive/CS6910/inaturalist_12K/train"
val_dir = "/content/drive/MyDrive/CS6910/inaturalist_12K/val"
```
3. Running the following cell executes the model
```
model = train(
    model,
    criterion,
    optimizer,
    scheduler,
    train_dl,
    val_dl,
    save_file_name="best.pth",
    max_epochs_stop=5,
    n_epochs=30,
    print_every=1)
 ```
 Here, parameters as optimizer, learning rate, scheduler, path to save best model and early stopping epoch patience can be set.
 
 
