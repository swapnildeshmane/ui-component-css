---
layout: docs
title: Sidebar
description: Examples and usage guidelines for sidebar.
group: components
---

Bootstrap provides One type of Sidebar.

## Contents

* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

## Expanded Sidebar YM required

{% example html %}
<div id="main-app" >
	<div class="yk-sidebar expanded-menu" >
		<div class="app-info-block">
			<div class="app-info-details">
				<span class="sidebar-toggler" >
					<span class="fa fa-bars" style="color:#fff;"></span>
				</span>
				<a class="brand-logo" href="">
					<img alt="LOGO">
				</a>
			</div>
			<div class="user-details">
				<div class="user-image">
					<img src="./usr.jpg">
				</div>
				<div class="user-name">
					admin@yuktamedia.com
				</div>
				<div class="user-role">
					Admin
				</div>
			</div>
		</div>
		<div class="yk-navigation sidebar-container ">
			<div class="app-group-block" >
				<span class="heading-text" >
					<span class="heading-text-icon"><i class="fa fa-angle-up" aria-hidden="true"></i></span>
					<span class="heading-text-label">Ad Operations</span>
				</span>
				<ul class="nav nav-sidebar">
					<li class="app-menu-item" >
						<a class="menu-link" href="" pf-app-loader="item" id="a-pixel-pinger">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
							<span class="link-text ">Pixel Pinger</span>
						</a>
					</li>
					<li class="app-menu-item">
						<a class="menu-link" href="" pf-app-loader="item" id="a-campaign-fulfilment">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
							<span class="link-text">Campaign Fulfilment</span>
						</a>
					</li>
					<li class="app-menu-item" >
						<a class="menu-link" href="" pf-app-loader="item" id="a-campaign-mapping">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
							<span class="link-text ng-binding">Campaign Mapping</span>
						</a>
					</li>
					<li class="app-menu-item" ng-repeat="item in app.items  track by $index">
						<a class="menu-link" href="" pf-app-loader="item" id="a-">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
							<span class="link-text ng-binding">360</span>
						</a>
					</li>
				</ul>
				<div class="user-info">
					<span class="heading-text">
						<span class="heading-text-icon"><i class="fa fa-angle-up" aria-hidden="true"></i></span>
						<span class="heading-text-label">My Profile</span>
					</span>
					<ul class="nav nav-sidebar">
						<li class="app-menu-item">
							<a class="menu-link" href="#">
								<i class="fa fa-sign-out" aria-hidden="true"></i>
								<span class="link-text">Logout</span>
							</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
     </div>
</div>
{% endexample %}

## Minimized Sidebar


{% example html %}
<div id="main-app" >
	<div class="yk-sidebar" >
		<div class="app-info-block">
			<div class="app-info-details">
				<span class="sidebar-toggler" >
					<span class="fa fa-bars" style="color:#fff;"></span>
				</span>
			</div>
			<div class="user-details">
				<div class="user-image">
					<img src="./usr.jpg">
				</div>
			</div>
		</div>
		<div class="yk-navigation sidebar-container ">
			<div class="app-group-block" >
				<span class="heading-text" >
					<span class="heading-text-icon"><i class="fa fa-angle-up" aria-hidden="true"></i></span>
				</span>
				<ul class="nav nav-sidebar">
					<li class="app-menu-item" >
						<a class="menu-link" href="" pf-app-loader="item" id="a-pixel-pinger">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
						</a>
					</li>
					<li class="app-menu-item">
						<a class="menu-link" href="" pf-app-loader="item" id="a-campaign-fulfilment">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
						</a>
					</li>
					<li class="app-menu-item" >
						<a class="menu-link" href="" pf-app-loader="item" id="a-campaign-mapping">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
						</a>
					</li><li class="app-menu-item" ng-repeat="item in app.items  track by $index">
						<a class="menu-link" href="" pf-app-loader="item" id="a-">
							<i class="fa fa-chevron-down" aria-hidden="true"></i>
						</a>
					</li>
				</ul>
				<div class="user-info">
					<span class="heading-text">
						<span class="heading-text-icon"><i class="fa fa-angle-up" aria-hidden="true"></i></span>
					</span>
					<ul class="nav nav-sidebar">
						<li class="app-menu-item">
							<a class="menu-link" href="#">
								<i class="fa fa-sign-out" aria-hidden="true"></i>
							</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
    </div>
</div>
{% endexample %}