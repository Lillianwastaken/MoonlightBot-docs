# Kick

### **Description**

This command is used to kick an user from the server.

### **Required arguments**

* `user` - The user you want to kick

### **Optional arguments**

* `reason` - The reason for the infraction. It will be shown in bot logs

### Flags

* `--dm-user` - Sends the reason for the warning to the user's DMs
* `--no-infraction` - Does not log an infraction. Log entry is still sent

### **Usage**

```
m:kick <user> [reason]
/kick <user> [reason]
```

{% hint style="info" %}
**The user must be userID or mention**
{% endhint %}

### **Aliases**

None

### **Required permission**

This command's level is 50 by default.\
The bot needs **Read Messages, Send Messages, Kick Members** permissions in order to be able to execute this command
