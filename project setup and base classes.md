package com.mycompany.poepart2;

public class PoePart2 {
    public static void main(String[] args) {
        
    }
}

package com.mycompany.poepart2;

public class Message {
    private String messageID;
    private String recipientCell;
    private String messageText;
    
    public Message(String messageID, String recipientCell, String messageText) {
        this.messageID = messageID;
        this.recipientCell = recipientCell;
        this.messageText = messageText;
    }
}
