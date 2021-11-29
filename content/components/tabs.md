---
layout: home
title: Tailwind CSS Tabs - Flowbite
description: Use these responsive tabs components to create a secondary navigational hierarchy for your website or toggle content inside a container
group: components
toc: true

previous: Modal
previousLink: components/modal
next: Navbar
nextLink: components/navbar
---

The tabs component can be used either as an extra navigational hierarchy complementing the main navbar or you can also use it to change content inside a container just below the tabs using the data attributes from Flowbite.

## Default tabs

Use the following HTML markup and Tailwind CSS utility classes to show a data set using a table component.

{{< example class="dark:bg-gray-900" >}}
<ul class="flex flex-wrap border-b border-gray-200 dark:border-gray-700">
    <li class="mr-2">
        <a href="#" aria-current="page" class="inline-block bg-gray-100 text-blue-600 rounded-t-lg py-4 px-4 text-sm font-medium text-center active dark:bg-gray-800 dark:text-blue-500">Profile</a>
    </li>
    <li class="mr-2">
        <a href="#" class="inline-block text-gray-500 hover:text-gray-600 hover:bg-gray-50 rounded-t-lg py-4 px-4 text-sm font-medium text-center dark:text-gray-400  dark:hover:bg-gray-800 dark:hover:text-gray-300">Dashboard</a>
    </li>
    <li class="mr-2">
        <a href="#" class="inline-block text-gray-500 hover:text-gray-600 hover:bg-gray-50 rounded-t-lg py-4 px-4 text-sm font-medium text-center dark:text-gray-400 dark:hover:bg-gray-800 dark:hover:text-gray-300">Settings</a>
    </li>
    <li class="mr-2">
        <a href="#" class="inline-block text-gray-500 hover:text-gray-600 hover:bg-gray-50 rounded-t-lg py-4 px-4 text-sm font-medium text-center dark:text-gray-400  dark:hover:bg-gray-800 dark:hover:text-gray-300">Contacts</a>
    </li>
    <li>
        <a class="inline-block text-gray-400 rounded-t-lg py-4 px-4 text-sm font-medium text-center dark:text-gray-500 cursor-not-allowed">Disabled</a>
    </li>
</ul>
{{< /example >}}

## Tabs with underline

Use the following HTML markup and Tailwind CSS utility classes to show a data set using a table component.

{{< example class="dark:bg-gray-900" >}}
<div class="border-b border-gray-200 dark:border-gray-700">
    <ul class="flex flex-wrap -mb-px">
        <li class="mr-2">
            <a href="#" class="inline-block text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300">Profile</a>
        </li>
        <li class="mr-2">
            <a href="#" class="inline-block text-blue-600 rounded-t-lg border-b-2 border-blue-600 py-4 px-4 text-sm font-medium text-center active dark:text-blue-500 dark:border-blue-500" aria-current="page">Dashboard</a>
        </li>
        <li class="mr-2">
            <a href="#" class="inline-block text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300">Settings</a>
        </li>
        <li class="mr-2">
            <a href="#" class="inline-block text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300">Contacts</a>
        </li>
        <li>
            <a class="inline-block text-gray-400 rounded-t-lg py-4 px-4 text-sm font-medium text-center dark:text-gray-500 cursor-not-allowed">Disabled</a>
        </li>
    </ul>
</div>
{{< /example >}}

## Tabs with icons

Use the following HTML markup and Tailwind CSS utility classes to show a data set using a table component.

{{< example class="dark:bg-gray-900" >}}
<div class="border-b border-gray-200 dark:border-gray-700">
    <ul class="flex flex-wrap -mb-px">
        <li class="mr-2">
            <a href="#" class="inline-flex text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300 group">
                <svg class="w-5 h-5 mr-2 text-gray-400 group-hover:text-gray-500 dark:text-gray-500 dark:group-hover:text-gray-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-6-3a2 2 0 11-4 0 2 2 0 014 0zm-2 4a5 5 0 00-4.546 2.916A5.986 5.986 0 0010 16a5.986 5.986 0 004.546-2.084A5 5 0 0010 11z" clip-rule="evenodd"></path></svg>Profile
            </a>
        </li>
        <li class="mr-2">
            <a href="#" class="inline-flex text-blue-600 rounded-t-lg border-b-2 border-blue-600 py-4 px-4 text-sm font-medium text-center active dark:text-blue-500 dark:border-blue-500 group" aria-current="page">
                <svg class="w-5 h-5 mr-2 text-blue-600 dark:text-blue-500" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M5 3a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2V5a2 2 0 00-2-2H5zM5 11a2 2 0 00-2 2v2a2 2 0 002 2h2a2 2 0 002-2v-2a2 2 0 00-2-2H5zM11 5a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V5zM11 13a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"></path></svg>Dashboard
            </a>
        </li>
        <li class="mr-2">
            <a href="#" class="inline-flex text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300 group">
                <svg class="w-5 h-5 mr-2 text-gray-400 group-hover:text-gray-500 dark:text-gray-500 dark:group-hover:text-gray-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M5 4a1 1 0 00-2 0v7.268a2 2 0 000 3.464V16a1 1 0 102 0v-1.268a2 2 0 000-3.464V4zM11 4a1 1 0 10-2 0v1.268a2 2 0 000 3.464V16a1 1 0 102 0V8.732a2 2 0 000-3.464V4zM16 3a1 1 0 011 1v7.268a2 2 0 010 3.464V16a1 1 0 11-2 0v-1.268a2 2 0 010-3.464V4a1 1 0 011-1z"></path></svg>Settings
            </a>
        </li>
        <li class="mr-2">
            <a href="#" class="inline-flex text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300 group">
                <svg class="w-5 h-5 mr-2 text-gray-400 group-hover:text-gray-500 dark:text-gray-500 dark:group-hover:text-gray-300" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z"></path><path fill-rule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm3 4a1 1 0 000 2h.01a1 1 0 100-2H7zm3 0a1 1 0 000 2h3a1 1 0 100-2h-3zm-3 4a1 1 0 100 2h.01a1 1 0 100-2H7zm3 0a1 1 0 100 2h3a1 1 0 100-2h-3z" clip-rule="evenodd"></path></svg>Contacts
            </a>
        </li>
        <li>
            <a class="inline-block text-gray-400 rounded-t-lg py-4 px-4 text-sm font-medium text-center dark:text-gray-500 cursor-not-allowed">Disabled</a>
        </li>
    </ul>
</div>
{{< /example >}}

## Tabs in pills

Use the following HTML markup and Tailwind CSS utility classes to show a data set using a table component.

{{< example class="dark:bg-gray-900" >}}
<ul class="flex flex-wrap">
    <li class="mr-2">
        <a href="#" class="inline-block bg-blue-600 text-white rounded-lg py-3 px-4 text-sm font-medium text-center active" aria-current="page">Tab 1</a>
    </li>
    <li class="mr-2">
        <a href="#"  class="inline-block text-gray-500 hover:text-gray-900 hover:bg-gray-100 rounded-lg py-3 px-4 text-sm font-medium text-center dark:text-gray-400 dark:hover:bg-gray-800 dark:hover:text-white">Tab 2</a>
    </li>
    <li class="mr-2">
        <a href="#" class="inline-block text-gray-500 hover:text-gray-900 hover:bg-gray-100 rounded-lg py-3 px-4 text-sm font-medium text-center  dark:text-gray-400 dark:hover:bg-gray-800 dark:hover:text-white">Tab 3</a>
    </li>
    <li>
        <a class="inline-block text-gray-400 py-3 px-4 text-sm font-medium text-center dark:text-gray-500 cursor-not-allowed">Tab 3</a>
    </li>
</ul>
{{< /example >}}

## Full width tabs

Use the following HTML markup and Tailwind CSS utility classes to show a data set using a table component.

{{< example class="dark:bg-gray-900" >}}
<div class="sm:hidden">
    <label for="tabs" class="sr-only">Select your country</label>
    <select id="tabs" class="bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-full p-2.5 dark:bg-gray-700 dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500">
        <option>Profile</option>
        <option>Canada</option>
        <option>France</option>
        <option>Germany</option>
    </select>
</div>
<ul class="hidden sm:flex rounded-lg shadow flex divide-x divide-gray-200 dark:divide-gray-700">
    <li class="w-full">
        <a href="#" class="w-full inline-block bg-gray-100 text-gray-900 rounded-l-lg py-4 px-4 text-sm font-medium text-center focus:ring-4 focus:ring-blue-300 relative focus:z-20 active dark:bg-gray-700 dark:text-white" aria-current="page">Profile</a>
    </li>
    <li class="w-full">
        <a href="#" class="w-full inline-block bg-white text-gray-500 hover:text-gray-700 py-4 px-4 text-sm font-medium text-center hover:bg-gray-50 focus:ring-4 focus:ring-blue-300 relative focus:z-20 dark:text-gray-400 dark:hover:text-white dark:bg-gray-800  dark:hover:bg-gray-700 dark:text-white">Dashboard</a>
    </li>
    <li class="w-full">
        <a href="#" class="w-full inline-block bg-white text-gray-500 hover:text-gray-700 py-4 px-4 text-sm font-medium text-center hover:bg-gray-50 focus:ring-4 focus:ring-blue-300 relative focus:z-20 dark:text-gray-400 dark:hover:text-white dark:bg-gray-800 dark:hover:bg-gray-700 dark:text-white">Settings</a>
    </li>
    <li class="w-full">
        <a href="#" class="w-full inline-block bg-white text-gray-500 hover:text-gray-700 rounded-r-lg py-4 px-4 text-sm font-medium text-center hover:bg-gray-50 focus:ring-4 focus:ring-blue-300 relative focus:z-20 dark:text-gray-400 dark:hover:text-white dark:bg-gray-800 dark:hover:bg-gray-700 dark:text-white">Invoice</a>
    </li>
</ul>
{{< /example >}}

<div class="mt-8 -mb-5">
  {{< requires_js >}}
</div>

## Interactive tabs

Use the dynamic tabs component to interactively show and hide the content below the tabs based on the currently active tab item. Make sure that you initialize the component by using the `data-tabs-toggle="{parentTabContentSelector}"` and also apply an `id` attribute to the same element.

Each tab toggle button needs to have a `role="tab"` attribute and a `data-tabs-target="{tabContentSelector}"` to target the tab content element that will be shown when clicked. You must also use the `aria-selected="true"` data attribute so that Flowbite can target the currently active tab component and hide it when another is shown.

You must also apply the `role="tabpanel"` data attribute to every tab content element and apply the `id` attribute which will be equal to the `data-tabs-target={tabContentSelector}` from the tabs toggles.

You can use multiple tab components on a single page but make sure that the id's are different.

{{< example class="dark:bg-gray-900" >}}
<div class="border-b border-gray-200 dark:border-gray-700 mb-4">
    <ul class="flex flex-wrap -mb-px" id="myTab" data-tabs-toggle="#myTabContent" role="tablist">
        <li class="mr-2" role="presentation">
            <button class="inline-block text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300" id="profile-tab" data-tabs-target="#profile" type="button" role="tab" aria-controls="profile" aria-selected="false">Profile</button>
        </li>
        <li class="mr-2" role="presentation">
            <button class="inline-block text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300 active" id="dashboard-tab" data-tabs-target="#dashboard" type="button" role="tab" aria-controls="dashboard" aria-selected="true">Dashboard</button>
        </li>
        <li class="mr-2" role="presentation">
            <button class="inline-block text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300" id="settings-tab" data-tabs-target="#settings" type="button" role="tab" aria-controls="settings" aria-selected="false">Settings</button>
        </li>
        <li role="presentation">
            <button class="inline-block text-gray-500 hover:text-gray-600 hover:border-gray-300 rounded-t-lg py-4 px-4 text-sm font-medium text-center border-transparent border-b-2 dark:text-gray-400 dark:hover:text-gray-300" id="contacts-tab" data-tabs-target="#contacts" type="button" role="tab" aria-controls="contacts" aria-selected="false">Contacts</button>
        </li>
    </ul>
</div>
<div id="myTabContent">
    <div class="bg-gray-50 p-4 rounded-lg dark:bg-gray-800 hidden" id="profile" role="tabpanel" aria-labelledby="profile-tab">
        <p class="text-gray-500 dark:text-gray-400 text-sm">This is some placeholder content the <strong class="font-medium text-gray-800 dark:text-white">Profile tab's associated content</strong>. Clicking another tab will toggle the visibility of this one for the next. The tab JavaScript swaps classes to control the content visibility and styling.</p>
    </div>
    <div class="bg-gray-50 p-4 rounded-lg dark:bg-gray-800" id="dashboard" role="tabpanel" aria-labelledby="dashboard-tab">
        <p class="text-gray-500 dark:text-gray-400 text-sm">This is some placeholder content the <strong class="font-medium text-gray-800 dark:text-white">Dashboard tab's associated content</strong>. Clicking another tab will toggle the visibility of this one for the next. The tab JavaScript swaps classes to control the content visibility and styling.</p>
    </div>
    <div class="bg-gray-50 p-4 rounded-lg dark:bg-gray-800 hidden" id="settings" role="tabpanel" aria-labelledby="settings-tab">
        <p class="text-gray-500 dark:text-gray-400 text-sm">This is some placeholder content the <strong class="font-medium text-gray-800 dark:text-white">Settings tab's associated content</strong>. Clicking another tab will toggle the visibility of this one for the next. The tab JavaScript swaps classes to control the content visibility and styling.</p>
    </div>
    <div class="bg-gray-50 p-4 rounded-lg dark:bg-gray-800 hidden" id="contacts" role="tabpanel" aria-labelledby="contacts-tab">
        <p class="text-gray-500 dark:text-gray-400 text-sm">This is some placeholder content the <strong class="font-medium text-gray-800 dark:text-white">Contacts tab's associated content</strong>. Clicking another tab will toggle the visibility of this one for the next. The tab JavaScript swaps classes to control the content visibility and styling.</p>
    </div>
</div>
{{< /example >}}

If you want to change the `active` style of the currently active tab from the default blue color just use the following selector in your CSS file and make sure that you also apply the `:hover` styles as well.

```css
[role="tab"].active {
    @apply text-red-600 border-red-600 dark:text-red-500 dark:border-red-500 hover:text-red-600 hover:border-red-600 dark:hover:text-red-500 dark:hover:border-red-500;
}
```