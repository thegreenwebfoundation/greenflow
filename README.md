# greenflow
A CLI tool to help you understand how network traffic moves across the real world, what powers it, its CO2 footprint.

## The dream:


> Chris Adams: It works by driving a headless browser to analyse a page. My interest has been to extend it further down the stack, and then expose this, so you'd be able to picture the digital footprint of an application by seeing where geographically the packets are routed form, and what power grids they pass thorugh.
>
> Emile Aben: that would work for both sitespeed and for traffic volumes captured by scapy / tshark , if i understand correctly
>
> Chris Adams: yes. as I've learned more, I've figured that starting with web worked for our use case, but really, we're just looking at traffic sent over TCP and UDP
>
> Emile Aben: trace_info_object = do_traces([[ ip1 , volume1 ], [ip2, volume2 ] .... ] )
>
> Emile Aben: and then analyse( trace_info_object ). -> produces a report
>
> Emile Aben: visualise( trace_info_object) => kick-ass viz of the thing
>
> Chris Adams: EXACTLY!. See the routes, and the CO2. Websites just make lots of parallel reqs and it's easy to debug them :)
>
> Emile Aben: trying to find the common thing (don't worry about the names of the functions just yet)
>
> Emile Aben: ok!
>
> Emile Aben: cool
>
> Emile Aben: we can do this.


## TODO

- [ ] make an actual readme
- [ ] make a starting changelog
- [ ] sketch out a plan, and make some issues
- [ ] actually start writing code
