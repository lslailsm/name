<!DOCTYPE html >
< html >
	<头>
		<元 字符集=“ utf-8 ” >
		< title >滤镜</ title >
		<样式 类型="文本/css " >
			图像{
				宽度： 500像素；
				高度：自动；
				显示：块；
				边距： 0自动；
				/* 滤镜 */
				/* 灰度灰度的一个设置 */
				-webkit-filter ： 灰度（1）；
				/* 展示时间 */
				过渡：全部1.5秒；
			}

			img :悬停{
				/* 鼠标放上来 */
				-webkit-过滤器：无；
			}

			. img1 {
				-webkit-filter ： 灰度（1）；
			}

			. img2 {
				/*亮度调节*/
				-webkit-filter ： 亮度（0.5）
			}
			. img3 {
				/* 棕褐色 */
				-webkit-过滤器： 棕褐色（1）；
			}
			. img4 {
				/* 模糊：可疑像素 */
				-webkit-filter ： 模糊（4像素）；
			}
			. img5 {
				/* 模糊：可疑像素 */
				-webkit-filter ： 饱和（1）模糊（10像素）亮度（10）灰度（1）；
				过渡：全部5秒；
				}
			}
			img5 ：悬停{
				/* 鼠标放上来 */
				-webkit-filter ： 饱和（1）模糊（0）亮度（1）灰度（1）；
			}
		</风格>
	</头>
	<身体>
		< img 类=" img1 " src =" img/44.jpeg " >
		< img 类=" img2 " src =" img/44.jpeg " >
		< img 类=" img3 " src =" img/44.jpeg " >
		< IMG 类= “ IMG4 ” SRC =“ IMG / 44.jpeg ” >
		< img 类=" img5 " src =" img/44.jpeg " >
	</正文>
</ html >
