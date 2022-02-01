css-Code für Board<br>
<style>

/* do not show topic 0 */
#section-0{
    display:none!important;
}
.topics {
    display: -webkit-inline-box;
}

/* 5 topics are shown on the display */
/* other topics are at the right side out of the visible area an can scrolled */
.course-content ul.topics li.section {
    width: calc(90vw/5 );
}

#section-6 .activity.modtype_label.label {
    float: left;
}
#section-6 .activity .actions {
    right: -50px;
}


div#region-main-box {
    padding-left: 0px;
    padding-right: 0px;
}
.row > div {
    padding: 0px!important;
}

.action-menu-item .filler {
 width: 0px;
}
.section_action_menu {
    margin-right: 10px;
}
.section li.activity {
    padding-left: 10px;
}


/* material label in card-style */
.labelcard {
    border: solid 1px #777;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    box-shadow: 0 0 0 #aaa;
    margin-left: 0px;
    margin-right: 5px;
    margin-top: 5px;
    margin-bottom: 5px;
    background-color: #fff;
}
/* use h5 in lable for a header */
.labelcard h5 {
    background-color: #103b9d;
    color: #fff;
    padding: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    border-bottom-left-radius: 0;
    border-bottom-right-radius: 0;
}
.labelcard p {
    padding-left: 10px;
}

/* if uploadarea is always visible this code makes it invisible */
.dndupload-hidden {
    display: none;
}

header#page-header {
    border-bottom: solid 1px #008;
}

/* color of the topic */
.sectionname a {
    color: #fff;
}

.path-course-view li.activity>div {
    padding: 0 0 0 0;
}
.section-modchooser-link.btn.btn-link {
    margin-right: 160px!important;
}

.course-content li.section ul {
    margin: 2px;
    padding-left: 0;
}

#region-main{
    background-color: #55bbff;
    border: 0px;
}
.card {
    border: 0px solid rgba(0,0,0,.125);
}
.card-body {
    background-color: #55bbff;
}
#page-navbar .breadcrumb li::after {
    border-left-color: #55bbff;
}
.section h3 {
    background-color: #e97d0e;
    padding: 6px;
    border: solid 0px #aaa;
    border-radius: 0px;
    margin-left: 10px;
    margin-right: 10px;
    color:#fff;
}


.course-content ul.topics li.section {
    border: 0px!important;

}



.course-content ul.topics li.section:nth-child(2n) {
    padding-top: 0rem!important;
    background-color: #55bbff;
}

.section .section-modchooser-text {
    display: none;
}
 .section .menu-action-text {
    display: none;
}


#page-content .section .d-inline-block.dropdown-toggle.icon-no-margin {
    visibility: hidden;
    font-size: 2px;
}
#page-content .section .d-inline-block.dropdown-toggle.icon-no-margin:after {
    font-size: 30px;
    visibility: visible;
}
.section .dropdown-item {
    display: contents!important;
}


/* code to be uses in editing mode  */
.editing .section .activity .mod-indent-outer {
    padding-left: 0;
}


 .editing_move .icon,
 .inplaceeditable .quickeditlink .icon,
 .section-handle .icon {
    color: #ddd!important;
}

.editing .section .activity .contentwithoutlink, 
.editing .section .activity .activityinstance {
    padding-right: 0px;
}

.section .label .contentwithoutlink, .section .label .activityinstance {
    padding-right: 0px;
}
.section .label .mod-indent-outer {
    padding-left: 0;
}
.section .activity.modtype_label.label {
    margin-left: 7px;
}


</style>
