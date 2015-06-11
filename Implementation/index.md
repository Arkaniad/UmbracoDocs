#Implementation
Get an overview of how the Umbraco pipeline is structured. See what happens from user request to content delivery.

<div class="row implementation">
	<div class="col-sm-12"></div>
</div>

<div class="row">
	<div class="col-xs-3">
		<small class="text-center">User Request</small>
		<span class="dot small">
			<span class="line v-line"></span>
		</span>

	</div>
	
	<div class="col-xs-9">
		<div class="row explain">
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot big icon-Tactics">
			<span class="line v-line top"></span>
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4 class="text-right"><a href="Routing/">Routing</a></h4>
			</div>
			<div class="col-xs-6">
				<h5><a href="Routing/MVC/">MVC</a></h5>
				<small>hits the <a href="">mvc controller</a> or a <a href="">custom controller</a></small>
			</div>	
			<div class="col-xs-6">
				<h5><a href="Routing/Pipeline/">Pipeline</a></h5>
				<small>Goes through the pipeline</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="Routing/Routing/">Routing</a></h5>
				<small>This section will describe how Umbraco Api controllers are routed and how to retreive their URLs</small>
			</div>
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot big icon-Folders">
			<span class="line v-line top"></span>
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4 class="text-right"><a href="Content-Definition/">Content Definition</a></h4>
			</div>
			<div class="col-xs-6">
				<h5><a href="Content-Definition/Documents/">Documents</a></h5>
				<small>Content has a content type that defines its data</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="Content-Definition/Media/">Media</a></h5>
				<small>It has a template that defines its presentation</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="Content-Definition/Members/">Members</a></h5>
				<small>Based on the schema a template is loaded</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="Content-Definition/Users/">Users</a></h5>
				<small>Based on the schema a template is loaded</small>
			</div>
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot big icon-Server-alt">
			<span class="line v-line top"></span>
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
		<span class="dot small">
			<span class="line v-line"></span>
			<span class="line h-line"></span>
		</span>
	</div>
	
	<div class="col-xs-9">
		<div class="row explain">
			<div class="col-xs-12">
				<h4><a href="Query-Data/">Query Data</a></h4>
			</div>
			<div class="col-xs-6">
				<h5><a href="Query-Data/UmbracoHelper/">Content/Media</a></h5>
				<small>Use UmbracoHelper to query published media and content</small>
			</div>
			<div class="col-xs-6">
				<h5><a href="Query-Data/MembershipHelper/">Members</a></h5>
				<small>This section covers the MembershipHelper</small>
			</div>
		</div>
	</div>
</div>

<div class="row">
	<div class="col-xs-3">
		<span class="dot small last">
			<span class="line v-line top"></span>
		</span>
		<small class="text-center">Content Delivery</small>

	</div>
</div>