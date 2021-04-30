# Form - Patterns

{% tabs %}
{% tab title="Overview" %}
### Overview

Over here, you can easily find common patterns to start building your site.

We provide baseline patterns that you can easily tweak to suit your products and services.

To bring you greater convenience, these patterns also have basic accessibility features built-in, e.g. autocomplete attributes for form fields.

For more information on WCAG standards , you can visit the [WCAG page](https://www.w3.org/WAI/standards-guidelines/wcag/).
{% endtab %}

{% tab title="Address" %}
### Address

Use this pattern when you require users to key in their Singapore-based address.

Note: Give your users the option to either key in their postal code to look up their address, or enter their full address manually.

![](../.gitbook/assets/image%20%2867%29.png)

```text
<div class="form-panel">
          <div class="form-panel-header">
            <h2>Address Details</h2>
          </div>
          <div class="form-panel-body">
            <div class="row">
              <div class="col-md-6">
                <div class="form-group">
                  <label class="col-form-label">Residential Status</label>
                  <input type="text" value="" class="form-control form-control-sm">
                </div>
                <div class="form-group">
                  <label class="col-form-label">Type of Housing</label>
                  <input type="text" value="" class="form-control form-control-sm">
                </div>
                <div class="form-group">
                  <label class="col-form-label">Type of HDB</label>
                  <input type="text" value="" class="form-control form-control-sm">
                </div>
                <div class="form-group">
                  <label class="col-form-label">Postal code</label>
                  <div class="input-group">
                    <input type="text" class="form-control form-control-xsm" placeholder="" aria-label="" aria-describedby="">
                    <div class="input-group-append">
                      <button class="btn btn-primary" type="button">Find</button>
                    </div>
                  </div>
                </div>
                <div class="form-group">
                  <label class="col-form-label">Block / house no.</label>
                  <input type="text" value="" class="form-control form-control-sm">
                </div>
                <div class="form-group">
                  <label class="col-form-label">Street Name</label>
                  <input type="text" value="" class="form-control">
                </div>
                <div class="multi-field">
                  <div class="form-group">
                    <label class="col-form-label">Floor no.<br>
                      (optional)</label>
                    <input type="text" class="form-control form-control-xxsm">
                  </div>
                  <div class="form-group">
                    <label class="col-form-label">Unit no.<br>
                      (optional)</label>
                    <input type="text" class="form-control form-control-xxsm">
                  </div>
                </div>
                <div class="form-group">
                  <label class="col-form-label">Building Name</label>
                  <input type="text" value="" class="form-control form-control-sm">
                </div>
                <div class="form-group">
                  <label class="col-form-label">Country</label>
                  <select class="form-control form-control-md">
                    <option value="">--- Select ---</option>
                    <option value="">Afghan</option>
                    <option value="">Albanian</option>
                    <option value="">Algerian</option>
                    <option value="">American</option>
                    <option value="">Andorran</option>
                    <option value="">Angolan</option>
                    <option value="">Antiguans</option>
                    <option value="">Argentinean</option>
                    <option value="">Armenian</option>
                    <option value="">Australian</option>
                    <option value="">Austrian</option>
                    <option value="">Azerbaijani</option>
                    <option value="">Bahamian</option>
                    <option value="">Bahraini</option>
                    <option value="">Bangladeshi</option>
                    <option value="">Barbadian</option>
                    <option value="">Barbudans</option>
                    <option value="">Batswana</option>
                    <option value="">Belarusian</option>
                    <option value="">Belgian</option>
                    <option value="">Belizean</option>
                    <option value="">Beninese</option>
                    <option value="">Bhutanese</option>
                    <option value="">Bolivian</option>
                    <option value="">Bosnian</option>
                    <option value="">Brazilian</option>
                    <option value="">British</option>
                    <option value="">Bruneian</option>
                    <option value="">Bulgarian</option>
                    <option value="">Burkinabe</option>
                    <option value="">Burmese</option>
                    <option value="">Burundian</option>
                    <option value="">Cambodian</option>
                    <option value="">Cameroonian</option>
                    <option value="">Canadian</option>
                    <option value="">Cape Verdean</option>
                    <option value="">Central African</option>
                    <option value="">Chadian</option>
                    <option value="">Chilean</option>
                    <option value="">Chinese</option>
                    <option value="">Colombian</option>
                    <option value="">Comoran</option>
                    <option value="">Congolese</option>
                    <option value="">Costa Rican</option>
                    <option value="">Croatian</option>
                    <option value="">Cuban</option>
                    <option value="">Cypriot</option>
                    <option value="">Czech</option>
                    <option value="">Danish</option>
                    <option value="">Djibouti</option>
                    <option value="">Dominican</option>
                    <option value="">Dutch</option>
                    <option value="">East Timorese</option>
                    <option value="">Ecuadorean</option>
                    <option value="">Egyptian</option>
                    <option value="">Emirian</option>
                    <option value="">Equatorial Guinean</option>
                    <option value="">Eritrean</option>
                    <option value="">Estonian</option>
                    <option value="">Ethiopian</option>
                    <option value="">Fijian</option>
                    <option value="">Filipino</option>
                    <option value="">Finnish</option>
                    <option value="">French</option>
                    <option value="">Gabonese</option>
                    <option value="">Gambian</option>
                    <option value="">Georgian</option>
                    <option value="">German</option>
                    <option value="">Ghanaian</option>
                    <option value="">Greek</option>
                    <option value="">Grenadian</option>
                    <option value="">Guatemalan</option>
                    <option value="">Guinea-Bissauan</option>
                    <option value="">Guinean</option>
                    <option value="">Guyanese</option>
                    <option value="">Haitian</option>
                    <option value="">Herzegovinian</option>
                    <option value="">Honduran</option>
                    <option value="">Hungarian</option>
                    <option value="">Icelander</option>
                    <option value="">I-Kiribati</option>
                    <option value="">Indian</option>
                    <option value="">Indonesian</option>
                    <option value="">Iranian</option>
                    <option value="">Iraqi</option>
                    <option value="">Irish</option>
                    <option value="">Israeli</option>
                    <option value="">Italian</option>
                    <option value="">Ivorian</option>
                    <option value="">Jamaican</option>
                    <option value="">Japanese</option>
                    <option value="">Jordanian</option>
                    <option value="">Kazakhstani</option>
                    <option value="">Kenyan</option>
                    <option value="">Kittian and Nevisian</option>
                    <option value="">Kuwaiti</option>
                    <option value="">Kyrgyz</option>
                    <option value="">Laotian</option>
                    <option value="">Latvian</option>
                    <option value="">Lebanese</option>
                    <option value="">Liberian</option>
                    <option value="">Libyan</option>
                    <option value="">Liechtensteiner</option>
                    <option value="">Lithuanian</option>
                    <option value="">Luxembourger</option>
                    <option value="">Macedonian</option>
                    <option value="">Malagasy</option>
                    <option value="">Malawian</option>
                    <option value="">Malaysian</option>
                    <option value="">Maldivian</option>
                    <option value="">Malian</option>
                    <option value="">Maltese</option>
                    <option value="">Marshallese</option>
                    <option value="">Mauritanian</option>
                    <option value="">Mauritian</option>
                    <option value="">Mexican</option>
                    <option value="">Micronesian</option>
                    <option value="">Moldovan</option>
                    <option value="">Monacan</option>
                    <option value="">Mongolian</option>
                    <option value="">Moroccan</option>
                    <option value="">Mosotho</option>
                    <option value="">Motswana</option>
                    <option value="">Mozambican</option>
                    <option value="">Namibian</option>
                    <option value="">Nauruan</option>
                    <option value="">Nepalese</option>
                    <option value="">New Zealander</option>
                    <option value="">Nicaraguan</option>
                    <option value="">Nigerian</option>
                    <option value="">Nigerien</option>
                    <option value="">Ni-Vanuatu</option>
                    <option value="">North Korean</option>
                    <option value="">Northern Irish</option>
                    <option value="">Norwegian</option>
                    <option value="">Omani</option>
                    <option value="">Others</option>
                    <option value="">Pakistani</option>
                    <option value="">Palauan</option>
                    <option value="">Panamanian</option>
                    <option value="">Papua New Guinean</option>
                    <option value="">Paraguayan</option>
                    <option value="">Peruvian</option>
                    <option value="">Polish</option>
                    <option value="">Portuguese</option>
                    <option value="">Qatari</option>
                    <option value="">Romanian</option>
                    <option value="">Russian</option>
                    <option value="">Rwandan</option>
                    <option value="">Saint Lucian</option>
                    <option value="">Salvadoran</option>
                    <option value="">Samoan</option>
                    <option value="">San Marinese</option>
                    <option value="">Sao Tomean</option>
                    <option value="">Saudi</option>
                    <option value="">Scottish</option>
                    <option value="">Senegalese</option>
                    <option value="">Serbian</option>
                    <option value="">Seychellois</option>
                    <option value="">Sierra Leonean</option>
                    <option value="">Singaporean</option>
                    <option value="">Slovakian</option>
                    <option value="">Slovenian</option>
                    <option value="">Solomon Islander</option>
                    <option value="">Somali</option>
                    <option value="">South African</option>
                    <option value="">South Korean</option>
                    <option value="">Spanish</option>
                    <option value="">Sri Lankan</option>
                    <option value="">Sudanese</option>
                    <option value="">Surinamer</option>
                    <option value="">Swazi</option>
                    <option value="">Swedish</option>
                    <option value="">Swiss</option>
                    <option value="">Syrian</option>
                    <option value="">Taiwanese</option>
                    <option value="">Tajik</option>
                    <option value="">Tanzanian</option>
                    <option value="">Thai</option>
                    <option value="">Togolese</option>
                    <option value="">Tongan</option>
                    <option value="">Trinidadian or Tobagonian</option>
                    <option value="">Tunisian</option>
                    <option value="">Turkish</option>
                    <option value="">Tuvaluan</option>
                    <option value="">Ugandan</option>
                    <option value="">Ukrainian</option>
                    <option value="">Uruguayan</option>
                    <option value="">Uzbekistani</option>
                    <option value="">Venezuelan</option>
                    <option value="">Vietnamese</option>
                    <option value="">Welsh</option>
                    <option value="">Yemenite</option>
                    <option value="">Zambian</option>
                    <option value="">Zimbabwean</option>
                  </select>
                </div>
              </div>
            </div>
          </div>
        </div>
```

### Guidelines

#### For your Address Lookup

* Make it clear to users that this will only work with Singapore addresses.
* Use the address lookup only if you are asking for a Singapore address. Otherwise, use multiple text inputs or a text area when asking for addresses outside of Singapore.

#### For Manually-entered Addresses

* The fields should always have the autocomplete attribute to help your users complete it quickly.
* You will need to include the autocomplete attribute to meet [WCAG 2.1 AA](https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html) for production.
{% endtab %}

{% tab title="Date" %}
### Date Input

Use this pattern when you want to ask users for a specific date, e.g their date of birth or when something was issued to them.

Note: If you need users to select from a few specific dates, we recommend that you use the radio button component to allow them to choose easily.

### Usage

Below you will find a General Date Format you can use, along with the code needed to build this element.  


### DD MM YYYY

![](../.gitbook/assets/image%20%2897%29.png)

### MM YYYY



### Guidelines

#### When you require users to fill in dates for your services

* State clearly how the data should be filled \(e.g. Day Month Year\)
* Give an example of how the date should be filled in \(e.g. 01 01 2020 vs 1 1 2020\)

#### When you request users to fill in memorable dates

* For example, asking for Date-Of-Birth means you should always have the autocomplete attribute for these 3 fields, bday-day, bday-month and bday-year to bring convenience to users.
* You will need to include the autocomplete attribute to meet [WCAG 2.1 AA](https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html) for production.
{% endtab %}

{% tab title="Email Address" %}
### Email address input

Use this pattern when you need to ask users for their email address.

Note: State clearly what their email address will be used for.

### Usage

Below you will find a General Email Address you can use, along with the code needed to build this element.

![](../.gitbook/assets/image%20%2864%29.png)

```text
<div class="form-group">
   <label class="col-form-label">Email</label>
   <input class="form-control" id="email" name="email" type="email" aria-describedby="email" autocomplete="email" spellcheck="false">
 </div>
```

### Guidelines

#### Explain the rationale of requesting for users’ email address

This allows users to:

* Feel assured that their email address will not be misappropriated
* Choose which email address they prefer to use

Make sure it works for all users

* Your field text should accommodate the maximum length of email addresses \(256 characters long, including punctuation\)

#### Guide users to enter their email address

Make it easier for users by:

* Allowing them to copy and paste their email address
* Setting the type attribute to email so that the correct keyboard is displayed
* Setting the spellcheck attribute to false so that their email addresses are not spell checked by the browser or device
* Setting the autocomplete attribute so that browsers can fill in their email address if they have entered it previously
* You will need to include the autocomplete attribute to meet [WCAG 2.1 AA](https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html) for production.
{% endtab %}

{% tab title="Names" %}
### Collecting Names

Use this pattern when you need to ask users for their names.

### Types

#### General name field

You should follow this pattern when you need to ask for a user’s name. You should only ask for names if you need it for a service.

![](../.gitbook/assets/image%20%2865%29.png)

```text
<div class="form-group required">
    <label class="col-form-label">Full Name</label>
    <input class="form-control">
    <small class="form-text text-muted">Enter full name as per ID document</small>
</div>
```
{% endtab %}
{% endtabs %}



