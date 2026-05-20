# wormulon

```
 _    _  _____  ____  __  __  __  __  __    _____  _  _ 
( \/\/ )(  _  )(  _ \(  \/  )(  )(  )(  )  (  _  )( \( )
 )    (  )(_)(  )   / )    (  )(__)(  )(__  )(_)(  )  ( 
(__/\__)(_____)(_)\_)(_/\/\_)(______)(____)(_____)(_)\_)
WORMULON :: A dummy slurm workload generator.
```

A script that schedules a set of fake batch jobs that mimic various slurm job types.

- GPU heavy work loads
- CPU heavy work loads
- Memory heavy work loads
- Array jobs of each
- Inappropriate resource requests
    - (too big or too small)

## Usage

```
wormulon [OPTION]...

-j, --jobs      number of total jobs to schedule

```

