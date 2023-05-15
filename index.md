# Easily Distracted and Hardly motivated

I am a data engineer that struggles with procrastination, attention, and motivation.
This blog is my attempt at putting my thoughts down, organising my mind and making
myself accountable. To whom? Well to who reads this, even if that's just myself.

My main issues are getting motivating myself for side projects without making things too
ambitious and getting stuck yak shaving until I lose interest. In my day job this
normally just manifests as tangents during my day which can end one of two ways:
fall down a rabbit hole and come out the other side with a solution to a problem
or lose a couple of hours. Either way, in the work context I'm less concerned.

But in my personal life, I want to be able to focus on things that I want to do
and make things that I find useful, rather than stopping with something half finished
and useless.

### Interests

I'm interested in programming first and foremost. I started programming during my
chemistry PhD and have since made a career out of it. I've always been interested
in data processing and analysis, and I've been lucky enough to be able to work on
public health projects for the last couple of years.

My areas of interest are:

- Productivity
- Data Engineering
- Python
- Elixir
- Rust
- PySpark
- Health
- Fitness

## Posts

{% for post in site.posts %}

- [{{ post.title }}]({{ post.url}})
  {% endfor %}
