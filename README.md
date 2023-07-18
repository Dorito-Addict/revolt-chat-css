# revolt-chat-css
This is a repository which includes the CSS code i use in Revolt Chat.

### Auto-hiding channel & members list
''' /* autohiding channel list */
[class^="ServerSidebar__ServerBase-sc-"]:hover {
    width: 232px;
    transition: 0.4s cubic-bezier(0.33, 1, 0.68, 1);
}

[class^="ServerSidebar__ServerBase"] {
    width: 50px;
    transition: 0.4s cubic-bezier(0.65, 0, 0.35, 1);
}

/* autohiding members list */
[class^="SidebarBase-sc-"]:nth-child(2):hover {
    width: 232px;
    transition: 0.4s cubic-bezier(0.33, 1, 0.68, 1);
}

[class^="SidebarBase-sc-"]:nth-child(2) {
    width: 54px;
    transition: 0.4s cubic-bezier(0.65, 0, 0.35, 1);
} '''
