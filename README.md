xhtml-email-boilerplate
=======================

html email base template



### Hiding sections in desktop email clients

#### sections with images

    <div class="mobile_only screen_max_480" style="display:none;height:0;max-height:0;overflow:hidden;"<img src="example.jpg" style="display:block;" border="0" /</div

#### sections with tables

    <div class="mobile_only screen_max_480" style="display:none;height:0;max-height:0;overflow:hidden;"
        <table width="100%" border="0" cellpadding="0" cellspacing="0" style="display:none"
            <tbody
                <tr
                    <td
                        <a href="#" target="_blank"<img src="example.jpg" style="display:block;" border="0" /</a
                    </td
                </tr
            </tbody
        </table
    </div

Note: `style="display:none"` in table is a workaround to prevent display in Outlook
