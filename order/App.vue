<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
			wx.cloud.init({
				traceUser:true,
				env:'panda-705n2'
			})
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
</style>
