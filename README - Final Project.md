# Week-7-Public

I've got an idea for the final project that is tied very closely to the day-to-day job I had as a Business Analyst while I was working in the US for a Tech company. If it doesn't work out, I'll probably go with the music page I'd like to create for myself, mentioned above.

1-I was responsible for doing market intelligence research in my job, using many different indicators (macro and micro economics). The objective was to rank countries or locations, where we could potentially open a new location and hire our employees (SDE mostly, which is kind of ironic!), based on multiple factors, such as our own internal recruiting, financial, and real estate metrics, and some other data we could obtain via public available websites like the OCDE, World Bank, IMF, and many others...
So I created different models in excel with some macros, where users could select the macro/micro indicators they were interested into, put some weight into those, based on the importance of those indicators, and obtain a ranked results for the locations we were assessing. The model was automated, with many calculations happening in the background, but the user only had to press a button to see what was happening after the criteria were selected.
We had plans to build a model out of excel, but really didn't have the time to do so. So I was thinking, it would be interesting to create the same kind of matrix, using html and tables, with some drop down menus for putting weights on the indicators, and have the data from those indicators coming from the World Bank through an API. I wouldn't be able to build it as complex as I had before (there were tons of sources and hundreds of indicators), but if I manage to build a simple version out of it, it would be really easy to iterate on it later, as it's not about the volume of data, just the logic of the formulas, and getting the automations working with both the API and everything else.
I checked the World Bank website, and their API is available for free, so I thought it could be an interesting project.

UPDATE: After checking in more details the World Bank API, it looks like many indicators are missing, especially the one I was interested in, like the Unemployment Rates and GDP values for instance. So I used the OECD's API instead in order to call the data into my table.


2-If my first idea turns to be overcomplicated and not really feasible, I would opt for the music website...which I would really need at some time eventually (in the next year or so...)
