# hotel_room_service_order_agent

A smart, fully working AI-powered room service chatbot built with LangChain + Google Gemini-2.5-flash.

What it does (works right now) :-
Understands natural questions: “What vegan options do you have?” / “Anything gluten-free?”
Shows real-time price and stock
Lets guests place orders → stock gets reduced automatically
Saves every order and conversation in MongoDB
Remembers past chat when you restart

Tech Stack :-
Python + LangChain (ReAct agent)
Google Gemini-2.5-flash
MongoDB (menu, orders, chat history)
Simple tools for search & order

How to run :-
pip install langchain langchain-google-genai langchain-mongodb pymongo
export GOOGLE_API_KEY=your-key
python upswing_hotel_agent.py

Just type your request and talk to the agent.

Current state :-
Clean, production-style prototype – fully functional end-to-end.
Ready for demo.

Enjoy!
