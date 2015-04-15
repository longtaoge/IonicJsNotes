      
### 获取当前星期几 ###

		/**
         * 获取当前星期几
         * @returns {}
         */
        var getweek = function () {

            var week;

            var today = new Date().getDay();

            if (today == 0)     week = "星期日";
            if (today == 1)     week = "星期一";
            if (today == 2)     week = "星期二";
            if (today == 3)     week = "星期三";
            if (today == 4)     week = "星期四";
            if (today == 5)     week = "星期五";
            if (today == 6)     week = "星期六";
            return week;
        };