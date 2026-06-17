# JMeter API Performance Testing

## Objective
Perform API testing and basic performance testing using Apache JMeter.

## API Tested
GET https://restful-booker.herokuapp.com/booking

## Test Configuration

| Parameter | Value |
|------------|---------|
| Users | 10 |
| Ramp-up | 5 seconds |
| Loop Count | 1 |

## Assertions
- Response Code = 200
- Response contains bookingid

## Results

| Metric | Result |
|----------|----------|
| Samples | 10 |
| Average Response Time | 1406 ms |
| Error Rate | 0.00% |
| Throughput | 1.7 requests/sec |

## Files
- restful-booker-get-bookings.jmx

## Tools
- Apache JMeter
- REST API Testing
