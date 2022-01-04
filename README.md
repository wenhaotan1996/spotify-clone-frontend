# Introduction  
This is frontend web application mocking Spotify's web player for educational purpose. The project was implemented using  
- [Next.js](https://nextjs.org/) 12 
- [NextAuth.js](https://next-auth.js.org/) 
- [Recoil](https://recoiljs.org/) 
- [Tailwind CSS](https://tailwindcss.com/)
- official [Spotify API](https://developer.spotify.com/)  
    
All information from authentication process to tracks and playlists are real data from Spotify official API.  
Due to the limitation of Spotify API's devlopment mode and limited functions to non-premium Spotify accounts, a demo using a deployment of the application is not practical.  
  
# Screenshots
![Screenshot 2022-01-03 213114](https://user-images.githubusercontent.com/38052117/148013773-913d01c3-068c-4b9f-a8c1-360036314671.png)
![Screenshot 2022-01-03 213804](https://user-images.githubusercontent.com/38052117/148014301-f27929df-5184-47cc-897b-4338dfee23af.png)
![Screenshot 2022-01-03 213035](https://user-images.githubusercontent.com/38052117/148013732-81303667-f3af-415b-9268-70358ab2b2b8.png)  
  
# To Recreate or Run the Application  
#### You will need  
- A Spotify developer account
- A premium Spotify account (required for playback control)
  
#### Set the following environment variables  
- NEXTAUTH_URL: the url to redirect to after autentication (e.g. http://localhost:3000)
- NEXT_PUBLIC_CLIENT_SECRET :acquired from Spotify API
- NEXT_PUBLIC_CLIENT_ID :acquired from Spotify AP
- JWT_SECRECT :secret string for JWT token
  


